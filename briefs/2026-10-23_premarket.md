# Pre-Market Brief: Fri Oct 23, 2026 (as of ~8:10 AM ET)
*This is information, not advice. Pre-market levels can still change before 9:30. No US 8:30 data today. First US data is at 9:45.*

## 1) Positioning (Quant Data GEX, gamma per 1% move)
| | Net GEX now (Oct 22 pre / Oct 22 close) | Call (+) walls | Put (−) walls | Flip |
|---|---|---|---|---|
| **SPY** 762.21 | **−6.41B** (−9.68B / **−15.45B**) | 800 (+0.52B), **767** (+0.51B), 770 (+0.46B) | **755** (−2.16B), **760** (−2.15B), 750 (−1.62B) | No cumulative flip. Strike sign change ~764–766 |
| **QQQ** 704.15 | **−2.44B** (−5.76B / −4.21B) | 720 (+0.18B), **715** (+0.14B), 730 (+0.13B) | **700** (−1.06B), 711 (−0.51B), 695 (−0.32B) | No cumulative flip. Sign change ~706–709 |
| **IWM** 275.26 | **−0.37B** (−0.64B / −2.02B) | 278 (+0.14B), 280, 290 | 277 (−0.15B), 270 (−0.15B), 273 (−0.14B) | Sign change 278. Thin data (18 strikes) |

- **Regime:** all three are in negative gamma, so dealers are likely to amplify moves. Pre-market is much less negative than Oct 22, and the walls have moved down (SPY call wall went from 780 to 767/770, QQQ from 725 to 715/720).
- **Oct 22 4:15 PM snapshot:** SPY put walls sat right at 763–765 (−3.0B at 765). QQQ had **+2.8B at 705**, which acts as a pin or magnet at yesterday's close.
- **Dark pool Oct 22:** SPY **763.76–763.78 (~$4.4B)**. QQQ **704.35–704.47 (~$1.4B)** and 702.0. IWM **276.36 ($0.35B)**. There were also large prints at SPY 773.12 ($2.05B) and QQQ 725.39 ($5.64B), but both are outside Oct 22's range, so they were likely late or negotiated prints.

## 2) Levels map (Team2Trading + GEX)
EMA stack is 2-min 13/48/200 on extended-hours data. PM = pre-market, 4:00 AM ET to ~8:06.

**SPY:** PDH 767.71 · PDL 761.16 · PDC 763.99 · PMH 764.95 · PML 761.58 · last 762.05
- EMA stack is **bearish** (13 762.29 < 48 762.34 < 200 763.07), with price below all three.
- Confluence:
  - **PDH 767.71 sits at the 767 call wall (0.09%)**.
  - **PDL 761.16 sits next to the 760 put wall (0.15%)**.
  - **PDC 763.99 lines up with the 763.77 dark pool level and the 764 sign change**.
- Untested zones: 764.25 (Oct 20 low), 765.82 (Oct 19 low), 768.40 (Oct 21 low; Casey's 767.84 key level), 770/770.46 (call wall + Oct 19 high).
- Plan: a 15-min close and retest above **764.95** opens calls toward 767/767.71. A 15-min close below **761.16** opens puts toward 760, then 755.
- Approx ES (×10.088): 764.95≈7717 · 767.7≈7745 · 761.16≈7679 · 760≈7667 · 755≈7616

**QQQ:** PDH 715.43 · PDL 701.90 · PDC 704.59 · PMH 708.14 · PML 703.32 · last 704.00
- EMA stack is **bearish** (704.34 < 704.37 < 704.86).
- Confluence:
  - **PDH 715.43 sits at the 715 call wall (0.06%)**.
  - **PDC/dark pool at 704.4–704.6 lines up with the 705 close-gamma magnet**.
  - PMH 708.14 sits inside the 708–709 sign-change zone.
  - PDL 701.90 is next to dark pool 702.0, with the 700 put wall 0.27% below.
- Untested zone: 710.39 (Oct 20 low), next to the 711 put wall.
- Plan: above **708.14** opens calls toward 710.4–711, then 715. Losing **701.90** opens puts toward 700, then 695.
- Approx NQ (×41.38): 708.14≈29302 · 711≈29421 · 715.4≈29604 · 701.9≈29044 · 700≈28965

**IWM:** PDH 277.28 · PDL 274.49 · PDC 276.69 · PMH 276.58 · PML 274.94 · last 275.26 (8:03)
- EMA stack is bearish-flat (13 275.32 = 48 275.32 < 200 275.74).
- Confluence: **PDH 277.28 sits at the 277 wall (0.10%)**, with the 278 call wall and Oct 21 high 277.70 just above. Dark pool 276.36 is inside the PM range.
- Plan: above **276.58**, then 277.28, opens calls toward 278. Losing **274.49** opens puts toward 273.
- Approx RTY ×10.11.

**Rules for today:**
- The PM range is a no-trade zone.
- Wait for a 15-min close beyond a level, and nothing before 9:45 ET.
- SPY and QQQ are below PDC and above PDL. If the open lands below PDL, PDL becomes resistance.
- **It's Friday, and Casey trades lightly on Fridays.**
- His latest X posts (Oct 22 evening) are promotional or break-and-flag recaps. **He hasn't posted levels for today yet.**

## 3) Flow: 9,000+ contracts
- **Oct 22:** 208 prints across all tickers. Full list: `history/flow_9k_2026-10-22.csv`.
- **Today's pre-market:** none as of ~8:08 AM ET.

Index prints, read by structure:
- **Put rolls down and out (taking profit on puts that had moved in the money), mostly multi-leg:**
  - 10:07: QQQ 710P 10/23, 21,030 sold below bid ($6.8M), paired with 690P 10/30, 16,123 bought above ask.
  - 11:28: QQQ 700P 10/30, 20k sold at bid ($16.3M), paired with 693P 11/6 bought at ask (opening).
  - 12:08: QQQ 696P 10/30 sold, 691P 11/6 bought, 10k each.
  - 15:41: QQQ 713P 11/6 (in the money), 12k sold at bid ($24.6M), paired with 680P 11/20 bought at ask.
  - Also SMH 530P 10/30 (in the money) sold, 500P 11/6 bought.
- **Hedges and collars:**
  - 10:58: QQQ 675P 11/30 bought at ask ($16M) and 760C sold at bid, 15k each.
  - 14:24: QQQ Dec31, 725C sold at bid (38k, $79M, opening) with 740C bought at ask. This is a 725/740 call spread credit, which caps upside above 725.
- **Put spreads:**
  - 09:48: SPY 736/728P 11/20, 16k each.
  - 10:44: SPY 690/590P Mar27, ~10k each.
  - 12:17: SPX 6800/6300P 11/6, 25k each.
  - 14:02: SPY 750/735P 10/30, a 1×2 ratio (12.5k by 25k).
- **Outright puts:**
  - 09:32: IWM 263P 11/20, 13,960 at ask ($3.0M).
  - 14:12: QQQ 680P 10/27, 10k at ask.
  - 15:25: SPY 730P 12/31, 10k at ask ($10.3M).
- **16:02 after the close: SPY 755P bought (ask) and 750P sold (bid), Mon 10/26 expiry, ~67k per leg across 5 same-timestamp clips.** This is a large short-dated put spread into the weekend and next week's FOMC.
- **VIX:** 10:27 multi-leg structures, mostly calls (55C and 60C at 100k each, mid). Some 15:34 VIX prints were flagged CANCEL.
- **What it adds up to:**
  - This flow is hedges being rolled and refreshed after a 2.9% NDX drop. It is **not the heavy put selling at the bid in deep negative GEX** that came before the Jun 11 and Jul 30 snap-backs.
  - The ITM-put monetization does take some downside fuel out.
  - The 10/26 put spread matches the study's **"short-dated put buying into an event, followed by whipsaw"** pattern.
  - Taken together, the flow doesn't clearly point to a sweep reversal or to trend continuation.
- **Historical note:** SPY's Oct 22 close at **−15.45B** almost exactly matches **Jun 10 (−15.46B)**, which came before a catalyst-driven snap-back on Jun 11. Pre-market has since eased to −6.4B. This is one comparison, not a signal.

## 4) Macro
**US data, ET:**
- 9:45: S&P Global flash PMIs. Manufacturing consensus 55.5 (prior 55.9). Services 58.0 (prior 58.8). Composite prior 58.4.
- 10:00: UMich sentiment final. Consensus 46.3 (prior 48.1).
- 8:30: Canada retail sales (consensus +1.3% m/m).
- No US 8:30 release. **The Fed is in blackout (Oct 17–29). FOMC is Oct 27–28.**

**Opex:** today is a **weekly expiry only**. Monthly opex was Oct 16, verified as the third Friday.

**Overnight data:**
- Euro-area PMIs missed: composite 51.9 vs 52.7 consensus, France 48.4.
- UK PMIs beat (53.1). UK retail sales came in at −0.4% m/m.
- Russia held at 14%.

**Earnings:**
- Thursday after the close: WDC −6%, DECK −7%, BE −5%, VRSN −5%, RNG +14%.
- Before today's open: AXP (EPS $4.68; revenue $20.06B vs $20.12B estimate), SLB beat (+0.9%), BAH +4.7%, INFY +3.7%, GNTX.
- Nothing index-moving after today's close was found.

**Headlines (Financial Juice RSS, X: @FirstSquawk, @DeItaone, @zerohedge, @LiveSquawk):**
- Thursday's AI and chip rout: NDX −2.9%, SOX −6.7%, META −7% on capex and share issuance, AMD −8%.
- In pre-market, META, NVDA, AMD and CRWV are bouncing.
- Telecoms are down more than 4% on a SpaceX competition report.
- **Oil is at a 5-month high**: Brent ~$114 on reports of possible US/Israel strikes on Iran. A Saudi coalition intercepted a Houthi missile at ~8:01 ET.
- Financial Juice's homepage didn't render; its RSS was used instead.

**Globex (since the 6 PM open) vs Oct 22 close:**
| | Last ~7:55 | ON high / low | vs Oct 22 |
|---|---|---|---|
| ES | 7687.50 | 7714.25 / 7678.00 | −17 (−0.22%) |
| NQ | 29131 | 29276.75 / 29022.75 | −11 (−0.04%) |
| RTY | 2782.1 | 2799.7 / 2776.9 | −14 (−0.50%) |

- **Asia:** Nikkei 62,693 (−0.3%), KOSPI +0.3%, Hang Seng ~23,093. Shanghai didn't fetch.
- **Europe:** DAX −0.8%, CAC −0.7%, FTSE −0.5%. STOXX 50 didn't fetch.
- **VIX** 19.63, up from 16.68 two days ago (ON range 18.87–19.90).
- **10-year** 4.95% as of Oct 22's close (no live quote); it fell from 5.15%.
- **Dollar index (DXY)** 101.83, **WTI** 100.77 (+1.3%), **gold** 4,037.8 (UBS calls $4,000 key support).

## Takeaway
- **The strongest confluence spots:**
  - SPY 767–767.7 (PDH plus call wall).
  - SPY 760–761.2 (PDL plus the biggest put wall).
  - QQQ 715–715.4 (PDH plus call wall).
  - The 704.4–705 magnet at yesterday's QQQ close.
- **Price is opening near those close and dark pool magnets**, inside the PM range, which is chop territory.
- Negative gamma means a 15-min break of the PM range could run toward the walls.
- Oil, Iran headlines and the 9:45/10:00 data are the catalysts to watch.
