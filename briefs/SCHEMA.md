# Brief feed schema (schema_version 1)

Base URL: `https://agustinooo.github.io/quant-desk/briefs/` (static JSON, `Access-Control-Allow-Origin: *`).
All times are US Eastern (`generated_at` carries its ET offset, e.g. `2026-10-30T08:10:00-04:00`).
Missing / unparsed values are `null` (arrays are `[]`). Numbers are never inferred beyond what the brief text states;
`markdown` always holds the full brief text, so anything not parsed is still there.

## Files
| File | Content |
|---|---|
| `latest.json` | most recent brief of any type (by `generated_at`) |
| `latest_premarket.json`, `latest_postdata.json`, `latest_close.json`, `latest_afterhours.json` | most recent of each type |
| `index.json` | `{updated_at, count, briefs:[{date,type,path,md_path,generated_at,summary}]}` newest first. `path` is relative to the site root (`/quant-desk/<path>`) |
| `YYYY-MM-DD_<type>.json` / `.md` | one brief, JSON + raw markdown |

Types: `premarket` (8:00 AM, includes that day's macro file if present), `postdata` (8:45 check), `close` (4:00 PM recap), `afterhours` (5:00 PM check).

## Brief object
```
{
  schema_version: 1,
  date: "YYYY-MM-DD",
  type: "premarket|postdata|close|afterhours",
  generated_at: ISO-8601 with ET offset,
  generated_at_source: "text" (time stated in the brief) | "file_mtime" | "scheduled_default" (type's usual time, used when the brief has no time),
  summary: first descriptive line of the brief (<=700 chars) | null,
  futures: { NQ|ES|RTY: { last, change_pct, high, low } },
      // pre-market/post-data/after-hours: high/low are overnight range when stated; close: RTH high/low. last is the
      // last price quoted in the text (close recap futures closes can be approximate; see markdown).
  tickers: { SPY|QQQ|IWM: {
      spot,                       // last/close price quoted in the brief
      pdh, pdl, pdc, pmh, pml,    // premarket: previous day high/low/close, pre-market high/low.
                                  // close: pdh/pdl/pdc = the NEXT session's levels (today's H/L/C); pmh/pml null.
                                  // postdata/afterhours: null (see markdown)
      net_gex_b,                  // net gamma exposure in $B per 1% move (negative = dealers short gamma)
      flip,                       // cumulative gamma flip strike if stated, else null
      sign_change,                // nearest strike where net gamma changes sign (string, may be a range "706-709")
      call_walls: [{strike, gex_b}], put_walls: [{strike, gex_b}],   // largest first as listed; gex_b null if not stated
      dark_pool: [{price, notional_b}],
      game_plan                   // text, premarket briefs that include one
  } },
  futures_levels: { NQ|ES: { pdh, pdl, pdc, pmh, pml, ratio_to_etf, approximate: true, basis } },
      // approximate futures equivalents. Computed ETF level x ratio only when the brief states the ratio; for close briefs, stated futures PDH/PDL.
  big_flow: [{ ticker, strike, expiry, cp: "C|P", size (contracts), premium (USD or null), side, time, read, raw }],
      // best-effort extraction of 9,000+ contract prints; `raw` is the source snippet. `read` is null (see markdown).
  macro: { calendar: [string], earnings: [string], headlines: [string],
           cross_asset: { vix, us10y, dxy, wti, brent, gold } },
  takeaway: string | null,
  markdown: full brief text,
  macro_markdown: that day's macro file text (premarket only) | null,
  source_file: "YYYY-MM-DD_<type>.md"
}
```
