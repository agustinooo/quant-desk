# Pre-Market Brief, Tue Nov 24, 2026 (data as of ~7:46 AM ET)

**Futures have given back a big part of Monday's NVDA-led rally overnight. Semis are leading the drop.** ES and NQ peaked at 20:10 last night and have been fading since, with lows printed around 06:15–07:35.
- **Futures (Yahoo, 7:35 ET, ~10 min delayed):**
  - **NQ 26302.75 (−1.88%)**, overnight range 26255 (06:15) to 27036 (20:10)
  - **ES 7176.75 (−1.07%)**, overnight range 7173.25 (07:25) to 7298.25 (20:10)
  - **RTY 2656.1 (−0.67%)**, overnight range 2655.5 (07:35) to 2688.7 (20:10)
  - All three are sitting near their overnight lows.
- **Semis are down hard:**
  - NVDA 157.12 (−4.8%), MU −6.1%, SMH −4.0%, AMD −3.8%, AVGO −3.1%, ORCL −2.9%, CRWV −4.6%
  - Anthropic (ANT) is trading below its $83 IPO price
  - Bitcoin is under $60k
- **I found no single overnight catalyst.** It looks like a fade of Monday's +31% NVDA squeeze. Two items are adding pressure:
  - AMD filed to register ~$152B of stock (the OpenAI/Meta warrants) for resale (X News).
  - Commerce blacklisted Megaspeed and six affiliates over AI-chip diversion (X News, ~7:46 ET).
- **VIX 29.21 (+9.7%)**, back near 29.4.
- **Gamma is negative across all three ETFs:**
  - **SPY −3.43B** (from −2.16B Monday morning)
  - **QQQ −1.59B** (from +0.07B)
  - IWM −0.55B
  - Dealers are short gamma, so moves can extend.
- **Where each ETF opens vs Monday's range:**
  - **QQQ is below its Monday low (641.95)**, so that level is resistance.
  - SPY and IWM are inside their Monday ranges, in the lower half.
- **Not a Friday and not OPEX, but it's Thanksgiving week:**
  - Core PCE, GDP and claims come Wednesday at 8:30.
  - Markets are closed Thursday and close at 1 PM Friday.

**Sources:**
- Quant Data API on your account: GEX by strike, dark pool, and 9k+ unconsolidated flow for Monday plus pre-market, pulled 7:46 ET
- Yahoo Finance: 1m/2m/15m/daily bars, futures, global markets, cross-asset
- Financial Juice RSS
- X News
- Last night's close recap and after-hours check for the calendar and earnings (Investing.com, Newsquawk)

**Caveats:**
- Positioning comes from the API, not the browser My Pages. The 'contract flow' Session Date was not touched (still May 29, 2026), and no filters were added.
- There's no heatmap or interval-map read, so the "magnets" are the largest GEX nodes.
- No cumulative gamma flip shows near spot. The levels listed are per-strike sign changes.
- Futures translations are approximate: ES ≈ SPY×10.02, NQ ≈ QQQ×41.07, RTY ≈ IWM×10.06.

---

## Positioning (Quant Data, 7:46 AM ET)

**SPY** (spot 715.87)
- **Net GEX −3.43B** (all) / −2.78B (ex-0DTE). Short gamma.
- **Put nodes:** **700 (−0.60B)**, 675 (−0.52B), 690 (−0.43B), 680 (−0.34B), **715 (−0.31B, right at spot)**.
- **Call walls:** **730 (+0.17B)**, 735 (+0.12B), 750 (+0.13B), 800 (+0.20B).
- **Per-strike pivots:** 720–723 (ex-0DTE), **726–728**, 734–735.
- **Dark pool:** the largest print today is **724.75**. Near spot, prints sit at 714.3–716.1.

**QQQ** (spot 640.44)
- **Net GEX −1.59B** (all) / −1.13B (ex-0DTE). It flipped from flat yesterday to short gamma.
- **Put nodes:** **640 (−0.37B, at spot)**, **635 (−0.37B)**, 600 (−0.35B), 630 (−0.26B), 620 (−0.24B).
- **Call walls:** 700 (+0.37B), 680 (+0.35B), 670 (+0.19B), 660 (+0.14B). These are far above.
- **Per-strike pivots:** 641–642, 644–645, 652, 655–656.
- **Dark pool:** the largest prints are at **653.3 and 651.7** (overhead). Near spot, they're at 639.4–640.8.

**IWM** (spot 263.98)
- **Net GEX −0.55B**. Short gamma, small.
- **Put nodes:** **255 (−0.19B)**, 240, 250 (−0.10B), 260 (−0.07B), 261 (−0.06B).
- **Call nodes:** **266 (+0.02B)**, 268 and 269 (+0.01B), 290.
- **Per-strike pivots:** 266, 270–271.
- **Dark pool:** **263.85** is by far the largest print.

### 9,000+ contract flow
**Pre-market today (to 7:46): none.**

**Monday Nov 23 (171 prints, all tickers; index/mega-cap highlights below, times ET):**
- **SPY hedges were rolled back up (11:29–11:32):**
  - Closed Friday's lowered hedges: 680P/660P 11/27 (66,750 each) and 650P/675P 12/4 (84,000/89,000).
  - Opened **700P/675P 12/11 and 12/7** (33,375 each, below bid, ~$74M combined).
  - **Read:** put support moved back to **700**, which is now SPY's #1 put node (−0.60B). This is a structural roll, not a directional sweep.
- **SPY 9:39:** opened 605P/535P 1/15, 75,000 each (605 at bid, 535 at ask). That's a same-timestamp spread: a 605/535 put-spread sale or a ratio. It's far-dated tail structure.
- **SPY 9:32:** closed 675P/570P 11/30, 75,000 each at the bid. That's a hedge being unwound into the gap up.
- **QQQ tail hedges:**
  - 10:11: opened 550P/450P 1/15, 48,911 each (550 at ask, 450 at bid). That's a bought put spread, ~$22M net.
  - 9:45: opened 500P 3/19 (15,000 at ask) and closed 600P 3/19.
- **QQQ put rolls in the afternoon:**
  - 15:12: closed 580P 12/18 (31,300 at ask) and opened **635P 12/18 (31,300 at the bid, $49.3M)**.
  - 12:56: closed 635P 12/4 at the ask and opened 585P at the bid.
  - These are same-timestamp rolls. Sides alone can't confirm buy vs sell, so treat them as structure, not a signal.
- **QQQ calls cashed in:** closed 700C 12/18, 30,000 total (10:54/11:00). Opened 720C 12/31 (~9.2–9.5k lots) and 680C 11/30 (10,000 at ask).
- **NVDA 10:35, a big tail-hedge package after the +31% day:** opened 120P 1/15 and 2/19 (100,000 each at ask, ~$41M), 80P 4/16 (150,000 total), and 80P 1/15 (150,000 at bid). Earlier, 170C 12/18 (~20,000) was opened at 9:30–9:33.
- **VIX:** closed 26C 12/16 (50,322 at the bid, ITM). That's vol-call profit-taking at 10:50.
- **IWM 9:41:** closed 251P/245P 12/18 (19,999 each).

**Read:**
- Monday's big prints were mostly **hedge rebuilding and profit-taking into the rally**, not a fresh trend bet: SPY puts re-struck at 700/675, NVDA and QQQ tail puts bought, QQQ/VIX calls closed.
- The overnight fade so far fits that caution. None of it is the "heavy put selling at the bid during deep negative GEX" pattern that came before the cleanest snap-backs in your study.
- Per your study, a lack of big prints this morning doesn't mean calm.

---

## Combined levels map (Team2Trading layer + GEX)

**The rules:**
- No trading inside the pre-market range.
- Wait for a 15-minute close beyond a level, and take nothing before 9:45 ET.
- Opening below the PDL makes it resistance.
- At the PDH/PDL, watch for break-and-retest vs rejection.

Pre-market high/low is 4:00 AM to 7:46 ET and can still change before 9:30. I filtered out odd 4:00 prints: raw SPY 725.16 and QQQ 654.00.

### SPY (pre-market 715.92 @7:45)
| Level | Price | ES ≈ | Notes |
|---|---|---|---|
| Untested R | 731.89 | 7337 | 11/19 15:45; **730 call wall** above |
| **PDH** | **727.98** | **7298** | **= the ES overnight high 7298.25**, plus the **726–728 GEX pivots**. **CONFLUENCE** |
| PMH | 723.80 (04:02) | 7256 | **724.3–725.0 15-min rejection cluster (Mon) + dark pool 724.75**. **CONFLUENCE** |
| 15-min zone | 719.0–720.6 | 7208–7224 | Mon supports; 720–723 ex-0DTE pivots |
| Fri high | 718.29 | 7200 | |
| **PML** | **714.30 (07:30)** | **7161** | **715 put node (−0.31B) + dark pool 714.3–715.9**. **CONFLUENCE** |
| **PDL** | **713.53** | **7153** | ~0.2% under the 715 node. Opening above it |
| Untested S | 711.72 | 7135 | 11/20 9:30 |
| Put wall | 700 | 7017 | #1 put node, rolled back up Monday |
- **2-min EMA stack:** 13 = 715.18 < 48 = 715.96 < 200 = 718.73. **Bearish**, but price is bunched between the 13 and 48.
- **Game plan (info, not advice):** Reclaim 724–725 and hold 15m, and calls toward 727.98 PDH / 730 wall. Lose 713.5 PDL on a 15m close, and puts toward 711.7, then 700 (put wall).

### QQQ (pre-market 640.49 @7:46)
| Level | Price | NQ ≈ | Notes |
|---|---|---|---|
| **PDH** | **657.50** | **27004** | Untested R 657.5 / 654.1 (Mon); 655–656 pivots |
| 15-min zone | 652.1–653.3 | 26782–26832 | Mon rejection cluster + **dark pool 651.7/653.3** + 652 pivot. **CONFLUENCE** |
| 15-min zone | 646.6–647.9 | 26556–26610 | Mon supports, now overhead |
| PMH | 646.11 (04:42) | 26536 | |
| Fri high / pivots | 643.28 / 644–645 | 26420–26490 | |
| **PDL** | **641.95** | **26365** | **641–642 GEX pivots**. Opening BELOW it, so it's resistance. **CONFLUENCE** |
| Put node / magnet | **640** | 26285 | **−0.37B, at spot, dark pool 639.4–640** |
| **PML** | **637.48 (06:16)** | **26181** | **635 put node (−0.37B)** sits 0.4% below |
| Untested S | 633.86 | 26033 | 11/20 9:30; 630 put node |
- **2-min EMA stack:** 13 = 639.57 < 48 = 640.13 < 200 = 643.98. **Bearish**. Price is just above the 13/48.
- **Game plan (info, not advice):** Reclaim and close 15m back above 641.95 PDL (the 642 pivot), and calls toward 646–647.9. Reject 641.95 / lose 637.5 PML, and puts toward 635 (put node), then 633.9.

### IWM (pre-market 264.00 @7:46)
| Level | Price | RTY ≈ | Notes |
|---|---|---|---|
| Untested R / pivots | 267.1–267.4, 270–271 | 2687–2692 | 11/19 |
| **PMH** | **266.36 (04:01)** | **2680** | **PDH 266.08 + 266 call node + 266 pivot + the 265.4–266.1 rejection cluster**. **CONFLUENCE** |
| **PDH** | **266.08** | **2677** | |
| **PML** | **263.68 (07:39)** | **2653** | **Dark pool 263.85 (largest) + Mon lows 263.85/263.99**. **CONFLUENCE** |
| **PDL** | **262.86** | **2645** | Untested S 262.62 (11/20) |
| Put nodes | 261 / 260 | 2626 / 2616 | |
| Put wall | 255 | 2565 | #1 put node |
- **2-min EMA stack:** 13 = 264.05 < 48 = 264.37 < 200 = 264.86. **Bearish / bunched**.
- **Game plan (info, not advice):** A 15m close over 266.1–266.4, and calls toward 267.1–267.4. Lose 262.86 PDL, and puts toward 261/260 (put nodes).

**Setup resemblance (/workspace/history):** this is negative gamma after a big relief rally that is now fading. In the past sample, most big moves both ways started in negative gamma. SPY's −3.4B is moderate, not the −15B to −29B extremes that came before the snap-backs.

---

## Macro and calendar (ET)
- **8:30:** no major US release on the calendar (per last night's recap: Investing.com/Newsquawk).
- **10:00:** Conference Board consumer confidence (consensus 92.1, prior 91.7), plus Richmond Fed manufacturing.
- **1:00 PM:** $70B 5-year note auction.
- **Earnings before the open:**
  - **ADI beat:** revenue $4.37B (+42% y/y) vs ~$4.32–4.33B consensus, adj. EPS $4.06 vs ~$3.88–3.90 (X News).
  - MDT also reports before the open (no result seen yet).
- **Earnings after the close today:** **DELL** (AI-server read-through), WDAY, ADSK.
- **After the close yesterday:**
  - HPE beat and raised but fell ~7% AH.
  - A +6.8%.
  - ZM beat and started a dividend.
  - Semtech beat and raised, but the stock is down.
- **Wednesday 8:30:** core PCE, the Q3 GDP revision and jobless claims. Thursday the market is closed; Friday it closes at 1 PM.
- **Fed:** Williams (last night) said inflation is still too high with upside risks, but "2027 will be a year of lower inflation". I didn't find a confirmed US Fed speaker schedule for today.

### Headlines (Financial Juice / X, overnight to now)
- **Hormuz:**
  - IRGC says another tanker hit a mine Tuesday (05:59).
  - UKMTO is getting late incident reports near Khor Fakkan and in Hormuz (03:25, 06:54).
  - Iran says it must "tighten Hormuz management" (03:49).
  - Saudi Arabia is asking allies for more missile interceptors (Semafor, 07:26).
- **China** suspended export controls on some dual-use items to the US (03:46).
- **Chips and AI:**
  - Commerce Entity-listed Megaspeed over AI-chip diversion.
  - Citi raised its NVDA target to $240 (06:10).
  - JPM cut its META target to $775 from $940 (04:22).
  - Axios reports Anthropic/OpenAI staff fear models are too unsafe to release (05:50).
- **ECB hawks:** Kaasik says rates must be raised. Simkus says to act preemptively.
- **German IFO** was 90.6 vs 90.5 expected.
- **JPM** sees the US 10-year peaking around 5.10% in Q1 2027.

### Global and cross-asset (Yahoo)
- **Asia:**
  - Nikkei +3.9% and Kospi +6.3%, catching up to Monday's US rally
  - Hang Seng −0.7%
  - Shanghai +0.3%
- **Europe:**
  - Euro Stoxx 50 −0.7%
  - DAX −0.8%
  - FTSE −0.2%
  - CAC +0.1%
- **VIX 29.21** (+9.7%; overnight range 26.26–29.41).
- **10-year 4.92%** (Monday close; no fresh Yahoo print yet).
- **DXY 103.95 (−0.4%).**
- **WTI 80.19** (flat; it settled under $80 intraday Monday for the first time since August on supply). Brent 86.94 (−2.7%).
- **Gold 3630 (−0.6%).** CME raises gold/silver margins after today's close.

---

## Takeaway (information, not advice)
- **The open is a gap down into short gamma, led by chips.**
- **The key confluence levels:**
  - **SPY 713.5–715** (PDL/PML + 715 put node + dark pool; ES ~7153–7161) and **724–725 / 728** (PMH + rejection cluster + dark pool 724.75; PDH = ES ON high 7298 + 726–728 pivots).
  - **QQQ 641.95–642** (PDL turned resistance + GEX pivots; NQ ~26365), the **640 magnet**, and the 637.5 PML with the 635 put node (NQ ~26080–26180).
  - **IWM 263.7–263.9** (PML + largest dark pool) and **266–266.4** (PDH/PMH + 266 call node).
- Below, the 700 SPY and 635 QQQ put walls are the next magnets if the lows break.
- **Respect the pre-market range as a no-trade zone, wait for 15-minute closes, and take nothing before 9:45.**
