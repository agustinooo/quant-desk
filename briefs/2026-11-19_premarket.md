# Pre-Market Brief, Thu Nov 19, 2026 (data as of ~7:48 AM ET)

**Big AI-led gap up after five down days.** Anthropic priced its record IPO at **$83, above the $70–78 range** (~$81B raised, ~$1.5T valuation). It starts trading on the Nasdaq today (Reuters). Futures at 7:35 ET (Yahoo, ~10–15 min delayed):
- **NQ 27742.75 (+2.05%)**
- **ES 7426.50 (+1.17%)**
- **RTY 2740.0 (+0.66%)**

**VIX is 22.36 (−9.0%).** Hyperscalers and semis are leading: GOOGL +3.9%, AVGO +2.9%, AMD +2.5%, AMZN +2.4%, NVDA +1.4%, CRWV +6.2%.

**SPY, QQQ and IWM are all opening ABOVE yesterday's highs.** Yesterday's high now acts as support. Each pre-market range is wide, and in this system that range is a no-trade zone.

**Positioning:**
- SPY: shallow short gamma, **−0.42B**.
- QQQ: **long gamma, +2.28B**, up from +0.75B.
- IWM: short gamma, **−1.01B**, down from −0.16B.

**Calendar:** 8:30 jobless claims and Philly Fed, Hammack at 8:50, 9:00 CB Leading Index. WMT and BABA reported this morning. **Tomorrow (Fri Nov 20) is monthly OPEX**, which Team2Trading trades lightly. Today is not OPEX.

**Sources:** Quant Data API on the user's account (GEX by strike, dark pool, 9k+ unconsolidated flow; pulled 7:48 ET), Yahoo Finance (1m/2m/15m bars, futures, global, cross-asset), Financial Juice RSS, X News, Reuters/Investing.com, CNBC/AP (WMT), XTB and Forex Factory (calendar), MarketScreener (10-year), and my 11/18 close recap.

**Caveats:**
- Positioning came from the Quant Data API, not the browser My Pages.
  - I didn't touch the 'contract flow' Session Date (May 29, 2026) and added no filters.
  - I didn't check the browser sign-in, but the API key worked.
- Yahoo futures quotes run about 10–15 minutes behind.
- There's no cumulative gamma flip near spot for SPY or IWM. QQQ's cumulative flip is far above at **696** (all expiries) / **705** (ex-0DTE).
- The "sign changes" below are per-strike pivots, not a true flip.

## Positioning (Quant Data, 7:48 AM ET)

**SPY** (spot 739.08)
- **Net GEX:** **−0.42B** (all expiries) / **−1.59B** (ex-0DTE). Mildly short gamma, which lets moves extend, but it's nowhere near the −15B to −29B readings in my history file.
- **Put walls:**
  - **700 (−0.80B)**
  - **736 (−0.36B, just below spot)**
  - **728 (−0.34B)**
  - 718 (−0.27B)
  - 722 (−0.27B)
- **Call walls:**
  - **750 (+0.89B, the biggest magnet above)**
  - 800 (+0.42B)
  - 755 (+0.28B)
  - 760 (+0.28B)
  - 748 (+0.25B)
- **Per-strike pivots:** sign changes at **735–736** and **738–740**, around spot.
- **Dark pool (pre-market):** clustered at **738.0–739.5**.

**QQQ** (spot 673.03)
- **Net GEX:** **+2.28B** (all) / +1.65B (ex-0DTE). Long gamma has tripled since yesterday, so expect dampening and pinning once the gap settles.
- **Put walls:**
  - **650 (−0.51B)**
  - 640 (−0.37B)
  - **680 (−0.29B, the negative node just above spot)**
  - 655 (−0.21B)
- **Call walls:**
  - **700 (+0.49B)**
  - 690 (+0.38B)
  - 720 (+0.33B)
  - 710 (+0.32B)
- **Per-strike pivots:** sign changes at **674–676** (ex-0DTE), **680–681**, and **659–661**.
- **Dark pool:** the biggest prints are at **672.80** and **671.45**.

**IWM** (spot 272.11)
- **Net GEX:** **−1.01B**. Short gamma, and the put side dominates.
- **Put walls:**
  - **270 (−0.50B, the largest)**
  - 271 (−0.22B)
  - 269 (−0.15B)
  - 272 (−0.13B)
- **Call side is thin:** 277 (+0.07B), 276, 274.
- **Per-strike pivots:** sign changes at **272.5–274**.
- **Dark pool:** light, around 271.7–272.0.

## 9,000+ contract flow

**Pre-market today:** **0 prints** of 9k+ so far (API, through 7:48).

**Prior session, Wed Nov 18:** 162 prints of 9k+ across all tickers (81 at the bid, 60 at the ask). The index-relevant ones, read by structure:

**SPY**
- **13:21: Nov 20 730P, 19,600 sold BELOW the bid ($10.1M), opening** (spot 731.4). This is aggressive short-dated put selling near the lows during negative gamma.
- **15:02: Mar '27 610P, 15,000 at the bid ($10.5M), opening.** A long-dated tail-hedge sale.
- **10:57 and 11:01: Nov 20 720P, 9,000 at the ask ($2.5M), and Dec 615P, 9,000 at the ask ($1.6M).** Hedges bought near the morning low. Both are tagged multi-leg.
- **10:40: Nov 20 716P / 718P, 12,500 each, closing.** A put spread being taken off.

**QQQ**
- **13:51: Dec 665P, 15,000 at the bid ($33.5M), opening.** In-the-money put selling.
- **11:19 (at the low):** Dec 675C bought at the ask, 10k ($13.6M), against Mar '27 675C sold at the bid ($33.8M). A calendar spread.
- **15:04: Nov 27 677C, 12,000 at the ask ($6.9M), opening.** Call buying into the close.
- **13:57: Nov 20 678C, 15,000 at the bid, opening.** Calls sold (overwrite/pin).
- **15:25 and 16:07: Dec 4-leg and 710C/715C clusters, all closing.** Rolls or closing trades.

**IWM**
- **16:03: Dec 258P / 257P, 9,257 each.** A put spread after the close.

**Other notable prints**
- **NVDA, 10:32:** Feb 175/185 call spread, **51,264** contracts (bought 175C at the ask for $38.4M, sold 185C at the bid).
- **NVDA, 10:12:** Jun '27 130P, 27,000 at the bid ($26.9M, opening). Put selling.
- **MSFT, 11:51:** deep-ITM Nov 420C sold (9,500, $77.8M) against Mar 450C bought. A roll, not a directional sale.
- **VIX:** multi-leg call and put structures, mostly closing.

**Read:** the standout is **heavy opening put selling at or below the bid** on Nov 18 in SPY (730P) and QQQ (665P), plus NVDA (130P), during negative SPY gamma. Today's gap up fits the pattern in my history file, where heavy put selling at the bid in negative GEX came before the cleanest snap-back rallies (Jun 10–11, Jul 28–30).
- **Caveat:** GEX was shallow (−0.83B), not deep like those cases. And the catalyst (the Anthropic pricing) came overnight.
- **So it looks more like a sweep reversal off the Nov 18 lows** (SPY 726.9 / QQQ 653.2 at 11:21) than trend continuation. Fully confirming that needs today's cash session to hold above yesterday's highs.

## Combined levels map (Team2Trading + GEX)

The pre-market high/low runs 4:00 AM to 7:48 AM ET and can still change before 9:30. ES/NQ/RTY numbers are **approximate**, using the 7:35 futures-to-ETF ratios (ES ≈ SPY×10.049, NQ ≈ QQQ×41.22, RTY ≈ IWM×10.07).

### SPY (pre-market 739.05)
- **Yesterday's high/low:** **734.99** (ES ~7386) / **726.90** (ES ~7304.5). Yesterday's close was 730.13.
- **Pre-market high/low:** **740.25 @06:55** (ES ~7438.5) / **734.49 @04:01** (ES ~7381).
- **15-minute untested support:** 729.45 (11/18 15:30), 727.16 / 726.79 (11/18 lows). No untested resistance until 760.12 (11/13 open).
- **2-minute EMAs:** 13 = 738.92, 48 = 739.00, 200 = 736.77. The 13 and 48 are **bunched (chop)**, sitting above a rising 200.
- **Confluence:**
  - ⭐ **734.5–736**: pre-market low 734.49 + yesterday's high 734.99 + the 736 put wall (−0.36B) + the 735–736 pivot (ES ~7381–7396). This is the key support shelf.
  - ⭐ **740.25**: pre-market high + the 740 per-strike pivot (ES ~7438.5).
  - ⭐ **726.9–728**: yesterday's low + the 728 put wall + the 15-minute lows (ES ~7304–7316).
  - **750 (+0.89B)** is the main upside magnet (ES ~7536).
- **Bias:** opening above yesterday's high makes that high support. Watch for a break-and-retest of 740.25 versus a rejection there. 734.5–740.25 is a wide no-trade box. Wait for a 15-minute close outside it, and nothing before 9:45.
- **Game plan:** 15-minute close above 740.25, and calls toward 745/748, then 750 (the biggest call wall). Lose 734.5–735 (yesterday's high/pre-market low), and puts toward 729.45, then 728/726.9.

### QQQ (pre-market 673.00)
- **Yesterday's high/low:** **662.68** (NQ ~27317) / **653.20** (NQ ~26926.5). Yesterday's close was 659.37.
- **Pre-market high/low:** **675.07 @06:47** (NQ ~27828) / **665.70 @04:10** (NQ ~27442).
- **15-minute untested resistance:** 681.70 (11/13 15:45; NQ ~28101.5) and 688.75.
- **15-minute untested support:** 657.12–657.22, 653.06–653.20.
- **2-minute EMAs:** 13 = 672.96, 48 = 673.28, 200 = 669.70. The 13 and 48 are **bunched**, above the 200.
- **Confluence:**
  - ⭐ **675.07**: pre-market high + the 674–676 pivot band (NQ ~27828).
  - ⭐ **680–681.7**: the 680 put node + the 680–681 pivot + 15-minute resistance at 681.7 (NQ ~28031–28101).
  - **665.7**: pre-market low, near the 667–668 ex-0DTE pivot. A looser match (~0.3%).
  - **660–662.7**: yesterday's high + the 659–661 pivot (NQ ~27207–27317). A looser match (~0.3%).
- **Bias:** opening about 1.5% above yesterday's high, so that high (662.68) is now far-off support. The pre-market range 665.7–675.07 (~1.4% wide) is the no-trade zone. Long gamma favors pinning toward strikes after the initial drive.
- **Game plan:** 15-minute close above 675.07, and calls toward 680/681.7. Lose 665.7, and puts toward 662.68/660.

### IWM (pre-market 272.06)
- **Yesterday's high/low:** **272.34** (RTY ~2743) / **267.99** (RTY ~2699). Yesterday's close was 270.08.
- **Pre-market high/low:** **272.29 @06:50** (RTY ~2742) / **270.81 @04:01** (RTY ~2727).
- **15-minute untested resistance:** 272.36 (11/18), **273.05–273.37** (11/16–17), 274.67–275.39.
- **2-minute EMAs:** 13 = 271.91, 48 = 271.86, 200 = 271.29. **Bullish but tightly bunched.**
- **Confluence:**
  - ⭐ **272.3–272.5**: yesterday's high + pre-market high + 15-minute resistance at 272.36 + the 272.5 pivot (RTY ~2742–2745). A triple stack right overhead.
  - ⭐ **270–270.8**: the 270 put wall (−0.50B) + yesterday's close at 270.08, with the pre-market low just above (RTY ~2719–2727).
  - **273.05–273.4**: 15-minute resistance cluster + the 273–274 pivots.
- **Bias:** IWM is the laggard, still inside or at yesterday's high. It's a break-and-retest vs rejection call at 272.3. Short gamma can make either side run.
- **Game plan:** 15-minute close above 272.35, and calls toward 273.05–273.4, then 274. Lose 270.81, and puts toward 270 (the put wall), then 269.

## Macro

**Calendar (ET; XTB / Forex Factory)**
- **8:30:** Initial jobless claims (consensus 198K, prior 200K) and **Philly Fed** (consensus 20.6, prior 20.9).
- **8:50:** Fed's Hammack. Vice Chair Jefferson is also listed (XTB), but I couldn't confirm the time.
- **9:00:** CB Leading Index m/m (consensus 0.0%, prior 0.0%).
- Possibly Goolsbee 12:30, Barkin 2:00 and Barr 2:15. Those come from a Nov 13 TD calendar snapshot, so they're unconfirmed.
- **Fed tone is hawkish.** The Oct minutes said nearly all officials saw a need for more rate increases (Reuters), and Kashkari spoke after the close yesterday. **The 10-year is about 5.09%** early (+2.1bp), and the 2-year 4.82% (MarketScreener).

**Earnings**
- **WMT (before the open):** adjusted EPS $0.65 and revenue $188.8B, both beats. It raised FY guidance to sales growth of 4.9–5.2% and EPS of $2.84–2.89. US comps were +2.9% ex-fuel, and e-commerce was +17%. Shares swung from about +1% to below −1% pre-market on slowing US comps (AP/CNBC).
- **BABA:** revenue +10%, AI cloud +53%, non-GAAP EPS missed (X News).
- **PANW (yesterday after the close):** about +8.3% after hours on a beat-and-raise. It's also buying Applied Compute for $4.5B in stock.
- **Anthropic IPO** trades today. That's the main sentiment catalyst for NQ.
- I didn't confirm tonight's after-close reporters.

**Headlines (Financial Juice / X, ET)**
- **00:39–05:54:** Trump–Xi meeting, then a **Trump–Xi–Putin trilateral in Shenzhen**.
  - Xi talked up a "constructive strategic stable relationship" and AI-safety cooperation.
  - Xi, Trump and Putin agreed to boost supply of refined oil products.
  - Trump said oil must flow through Hormuz.
  - A joint statement is due.
- **04:59: Iran (Fars): 2 tankers hit a mine in eastern Hormuz.** **07:29: the White House asked the Pentagon for Iran scenario assessments (Axios).** This is the geopolitical tail risk.
- **05:23: TSMC and Samsung suspend some chip shipments to Chinese customers** while applying for US Commerce licences (FT). A semis headline risk.
- **01:19:** drones hit oil storage in Russia's Tatarstan.
- **06:31:** the US is weighing more diesel and oil exports to Europe (Energy Sec. Wright).
- ECB's Nagel said a hike "would send a clear signal." Kushner and Witkoff are heading to Berlin on Ukraine.

**Globex (since 18:00 ET)**

| | Last (07:35) | Change | Overnight high | Overnight low |
|---|---|---|---|---|
| NQ | 27742.75 | +2.05% | 27830.50 (06:45) | 27169.00 (18:00) |
| ES | 7426.50 | +1.17% | 7440.50 (06:55) | 7338.25 (18:00) |
| RTY | 2740.0 | +0.66% | 2743.2 (06:30) | 2721.0 (18:00) |

These are one-way gaps that are holding near the overnight highs. Yesterday's settles were NQ 27186.75 / ES 7340.50 / RTY 2722.0, which is where the unfilled gaps sit.

**Global markets**
- **Asia:** Nikkei +0.7%, Kospi +1.4%, Hang Seng −1.9%, Shanghai −0.3%.
- **Europe:** Stoxx 50 +0.4%, DAX flat, CAC flat, FTSE −0.4%. All are off their 3–4 AM highs.

**Cross-asset**
- **VIX:** 22.36 (−9.0%).
- **Dollar (DXY):** 103.74 (−0.1%).
- **Oil:** WTI 83.09 (−0.2%), Brent 90.07 (−2.0%).
- **Gold:** 3716 (−0.7%).

## Takeaway (information, not advice)
- **SPY:** the key level is **734.5–736** (yesterday's high + pre-market low + the 736 put wall). Holding it keeps the gap intact, with **750 (+0.89B)** as the magnet above.
- **QQQ:** in long gamma, **675.07** (pre-market high + pivot) and **680–681.7** are the levels to break. Below the pre-market low at **665.7**, the gap-fill risk is toward 662.7/660.
- **IWM:** stuck under a **272.3–272.5 triple stack**, with the **270 put wall** below. Short gamma means a 15-minute close beyond either side can run.
- **Risks:** 8:30 data, Hammack at 8:50, the Hormuz/Iran headlines, the TSMC/Samsung China-shipment story, and the Anthropic debut tape. Wide pre-market ranges mean waiting for 9:45 and a 15-minute close.
