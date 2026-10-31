# Pre-Market Brief: Mon Oct 26, 2026 (as of ~8:15 AM ET)
*Information, not advice. Pre-market levels can still change before 9:30. Today's only US data is the 8:30 Chicago Fed index; FOMC starts tomorrow.*

## 1) Positioning (Quant Data, gamma per 1% move, ~8:12 AM ET)
| | Net GEX now (ex-0DTE) / Fri close | Call walls | Put walls | Flip |
|---|---|---|---|---|
| **SPY** 763.03 | **−5.52B** (−3.74B) / −22.38B | **770** (+0.56B), 780 (+0.43B), **765** (+0.41B) | **755** (−3.53B, about 1.5B of it expires today), 745 (−1.23B), 750 (−1.19B), **760** (−1.00B) | No cumulative flip. Strikes change sign around 761–763 and 766 |
| **QQQ** 709.10 | **−1.48B** (−1.72B) / −4.46B | 725 (+0.28B), 720, 730, **715** (+0.18B) | **700** (−0.85B), 690 (−0.83B), 680, 695 | No cumulative flip. Strikes change sign around 707–708 and 710–711 |
| **IWM** 276.44 | **+0.16B** (≈0) / −1.59B | 282, 280, 276 (all small) | **275** (−0.15B) | Cumulative flip at 282. Thin data (24 strikes) |

- SPY and QQQ are still in negative gamma, but far less negative than Friday's close as futures gap up. IWM is about flat, so expect less dealer help there.
- **The 755 SPY put wall is the biggest node on the board.** It lines up with Friday's huge 10/30 put trade (see Flow).
- **Dark pool, Oct 23:** SPY **763.81** ($2.16B) and a 759.84–759.97 cluster (~$1.4B). QQQ 704.35–704.40 (~$1.4B) and 705.10. IWM 275.67–275.87.

## 2) Levels map (Team2Trading + GEX)
PM is the pre-market range, 4:00 AM ET to 8:11 AM. The EMA stack is the 2-minute 13/48/200.

**SPY:** PDH 763.47 · PDL 758.68 · PDC 759.91 · PMH 763.23 · PML 760.00 · last 763.03
- The EMA stack is **bullish** (762.53 > 761.73 > 761.40).
- Price is pressing the top of the PM range, right under PDH.
- **Confluence:**
  - **The PMH/PDH zone at 763.2–763.5 sits with the 763.81 dark pool level and the 763 sign change.** That's the first big gate.
  - **PML 760.00 is exactly the 760 put wall**, near the 759.9 dark pool and PDC.
  - **The 770 call wall sits with the Oct 19 high at 770.46.**
- Untested zones above: 764.25 (Oct 20 low), 765 (call wall) to 765.82 (Oct 19 low), 767.71 (Oct 22 high), 768.40 (Oct 21 low).
- Untested zones below: 760.64 (Oct 16 low), 758.68, then the 755 wall.
- **Plan:** a 15-min close above **763.5** and a retest opens calls toward 765–765.8, then 767.7. Losing **760** opens puts toward 758.7, then 755.
- Approx ES (×10.07): 763.5≈7691 · 765≈7707 · 767.7≈7734 · 770≈7757 · 760≈7656 · 758.7≈7643 · 755≈7606

**QQQ:** PDH 709.30 · PDL 701.16 · PDC 704.39 · PMH 709.75 · PML 702.09 · last 709.09
- The EMA stack is **bullish** (708.28 > 706.58 > 705.66).
- Price is above PDH, which turns PDH into the first support to retest.
- **Confluence:**
  - **709.3–710.4 holds PDH, PMH, the 710–711 sign change and the Oct 20 low at 710.39.** That's the breakout gate.
  - **The 715 call wall sits with the Oct 22 high at 715.43 (0.06%).**
  - **The 700 put wall sits with PDL 701.16 (0.17%).**
- 704.4 holds PDC plus the dark pool cluster, and 707.23 is the Oct 16 low.
- **Plan:** a 15-min close above **710.4** opens calls toward 715–715.4. A failure back under **709.3** traps buyers and opens puts toward 707.2, then 704.4.
- Approx NQ (×41.29): 710.4≈29332 · 709.3≈29287 · 715.4≈29540 · 707.2≈29202 · 704.4≈29085 · 701.2≈28951 · 700≈28903

**IWM:** PDH 276.24 · PDL 273.35 · PDC 275.72 · PMH 276.93 (at 4:01) · PML 275.76 · last 276.48
- The EMA stack is mildly bullish (276.47 > 276.31 > 276.14).
- **Confluence:**
  - **The 275 put wall sits with the Oct 21 low at 275.30 (0.1%).**
  - The 276 sign change sits at PDH 276.24.
- Overhead: Oct 20 high 276.90 and PMH 276.93, then 277.28 and 277.70 (Oct 22 and Oct 21 highs).
- **Plan:** a close above **276.93** opens calls toward 277.3–277.7. Losing **275.76**, then 275.3, opens puts toward 275, then 273.35.
- Approx RTY (×10.10): 276.93≈2797 · 277.7≈2804 · 276.24≈2790 · 275.76≈2785 · 275≈2777

**Rules for today:**
- The PM range is a no-trade zone.
- Wait for a 15-min close beyond a level, and nothing before 9:45.
- QQQ and IWM are opening above PDH, so watch for break-and-retest versus a rejection back inside.
- **@Team2Trading hasn't posted levels for today** as of 8:05.

## 3) Flow: 9,000+ contracts
- **Today's pre-market:** none as of 8:12.
- **Fri Oct 23:** 228 prints across all tickers. Full list: `history/flow_9k_2026-10-23.csv`.

**Main index prints, read by structure:**
- **14:39:51, SPY 10/30, one multi-leg ticket with SPY at 760.23:**
  - **Bought 755P, 138,262 contracts above the ask, opening, $67.3M.**
  - Sold 760P, 55k at the bid, $36.6M.
  - 745P traded 26k at the bid and 57k at the ask.
  - This is a large put structure centered on 755, expiring Friday after FOMC, GDP and PCE. **It's why 755 is now the dominant put wall.**
- **14:38, QQQ 10/30:** 700P and 675P traded 16.6k each **below the bid**, which is likely closing a put spread.
- **13:28, QQQ:** sold the in-the-money 713P 11/6 at the bid (10k, $18.2M) and bought the 680P 11/20 at the ask. It's the same roll down and out as Thursday, taking profit on puts that had moved in the money.
- **12:41, SPY 10/30:** 750P and 735P, 9.8k each at the bid (a put spread).
- **IWM, heavy Nov/Jan put hedging, all multi-leg spreads:**
  - 09:40: 261/263P 11/20, 36k each.
  - 09:42: 250/270P Jan, bought at the ask.
  - 10:47: 225P Dec '27, opening.
  - 14:06: 275/260P 11/20.
  - 16:03: 261/262P 11/20, 28k each.
- **VIX:** Nov call spreads and put sales through the day, and 19P Jan bought at the ask (10k).
- **What it adds up to:**
  - This is hedging into FOMC and month-end, **not the heavy put selling at the bid in deep negative GEX** that came before the cleanest snap-backs in the user's study.
  - Thursday's 10/26 755/750 put spread (~67k) expires today far out of the money.
  - The 755-centered 10/30 trade fits the study's **"short-dated put buying into an event, followed by whipsaw"** pattern.
  - No clear sweep-reversal or trend-continuation signal.
- **Historical note:** Friday's SPY close at **−22.38B** is about the same as **Jul 29 (−22.9B)**, which preceded a sharp snap-back rally. This morning's gap up looks like that kind of relief, but it's one comparison, not a signal.

## 4) Macro
**US data, ET:**
- 8:30: Chicago Fed National Activity Index. Consensus −0.10, prior −0.04.
- 10:30: Dallas Fed manufacturing. Consensus 7, prior 9.8.
- 1:00 PM: $69B 2-year auction.
- No Fed speakers (blackout).

**Week ahead:**
- Tue: durable goods and consumer confidence. FOMC begins.
- **Wed 2:00 PM: FOMC decision, then Chair Warsh's press conference at 2:30.** MSFT and GOOGL report after the close.
- **Thu 8:30: Q3 GDP and Sep PCE.** AMZN reports after the close.
- Fri: ECI. XOM and CVX report before the open.

**Earnings:**
- **This morning:** VZ beat on EPS and missed on revenue; it raised guidance and is about +2%.
- **After today's close:** CDNS, NUE, AMKR, CLS, RMBS.
- Friday after the close: nothing index-moving.
- **Movers:**
  - Brazil ADRs are crashing after Lula's 4th-term win (XP −48%).
  - CoreWeave and other neoclouds are lower on a Musk "reckoning" warning.
  - TSLA +2% on an upgrade.
  - MRNA −8%.

**Headlines (Financial Juice RSS, X):**
- **META is raising ~$35B in stock and convertible preferred.** NVDA, AMD and AVGO indicated interest in buying up to $5B. META swung from −2.3% to +2.2% pre-market.
- **The Anthropic S-1 is due at 9:00 AM ET.**
- SpaceX signed a $40B GPU lease with Apollo.
- **Iran tone is de-escalating** (Qatar is mediating and Saudi Arabia cites talks), and oil is lower.
- Germany's Ifo came in at 90.2 vs 89.9 expected.

**Globex (yfinance, about 10–15 min delayed, ~8:02):**
| | Last | ON high / low | vs Fri close |
|---|---|---|---|
| ES | 7686.25 | 7697.75 / 7651.75 | +23 (+0.30%) |
| NQ | 29279.50 | 29345.00 / 29024.25 | +140.5 (+0.48%) |
| RTY | 2792.1 | 2799.6 / 2784.9 | +6.2 (+0.22%) |

- Futures gapped up at the Sunday open, dipped to the overnight lows, and recovered.

**Global, vol and rates:**
- **Asia:** Nikkei −0.8%, KOSPI −1.5%, Hang Seng +0.5%, Shanghai +0.2%.
- **Europe:** DAX +1.0%, CAC +0.8%, FTSE +0.4%, STOXX 50 +0.7%.
- **VIX** 19.14 (−3.3%). Front-month VIX future 19.25. VVIX was 109.7 on Friday.
- **10-year** 5.007% (+1.9 bp, back above 5%). **2-year** 4.718%.
- **Dollar index** 101.90. **WTI** 101.04 (−2.5%). **Gold** 4,031.7 (+0.5%).
- **Expiry:** daily expiries only today. It isn't Friday or a monthly opex; the 10/30 month-end expiry comes Friday.

## Takeaway
- **The key confluence levels:**
  - **SPY 763.2–763.8:** PDH, PMH and the dark pool level, a gate right at spot.
  - **SPY 760:** PML plus the put wall.
  - **SPY 770:** the call wall plus the Oct 19 high.
  - **QQQ 709.3–710.4:** PDH, PMH and the sign change.
  - **QQQ 715–715.4:** the call wall plus the Oct 22 high.
  - **QQQ 700–701.2:** the put wall plus PDL.
- The biggest magnet below is **SPY 755**.
- Negative gamma, though shrinking, means a clean 15-min break of the PM range can travel wall to wall.
- Bonds back above 5% and the 9:00 Anthropic filing are the morning wildcards, and FOMC risk builds into Wednesday.
