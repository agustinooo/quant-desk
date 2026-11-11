# Pre-Market Brief, Wed Nov 11, 2026 (Veterans Day; data as of ~7:50 AM ET)

**Risk-on gap up, led by chips.** As of ~7:35–7:40 ET (Yahoo): **NQ 28386.5 (+1.98%)**, **ES 7612.5 (+0.90%)**, **RTY 2852.0 (+0.82%)**, all sitting at their overnight highs. **All three ETFs are trading above yesterday's highs**, so the PDHs are now support to retest. The catalyst is **CoreWeave**: it raised 2026 revenue guidance to $13–13.3B (consensus $12.9B) and the stock is +16% pre-market. That's driving a chip rebound: NVDA +4.0% (175.71), AMD +6.3%, AVGO +4.3%. VIX is **18.48 (−5%)**. Dealers swung from deep short gamma last night to **long gamma in SPY**, so expect a more pinned, magnet-driven tape than earlier this week.

**What's different today:**
- The bond market is closed for Veterans Day (stocks open), so liquidity is thinner. There's no US data of note.
- It's not a Friday and not monthly OPEX (that's Nov 20).

**Sources:** the Quant Data API on the user's account (GEX by strike, dark pool, 9k+ unconsolidated flow; pulled 7:48 ET), Yahoo Finance (1m/2m/15m/5m/daily), the Financial Juice RSS feed, X (Team2Trading, X News), and Reuters, Investing.com, CNBC and Yahoo for the morning wrap and calendar. **Caveats:**
- Positioning came from the Quant Data API, not the browser My Pages tabs, which weren't checked this run. "Magnets" means the largest GEX strike nodes plus dark-pool clusters.
- The prior-session 9k+ flow is from last night's close pull.

## Positioning (Quant Data, Nov 11 7:48 AM snapshot)
**The regime flipped:** last night SPY carried about −5B ex-0DTE. This morning SPY is solidly long gamma, QQQ is modestly long, and IWM is flat.

- **SPY** (spot ~756.8):
  - **Net GEX:** **+6.45B** all expirations, **+3.46B** ex-0DTE.
  - **Call walls:** **760 (+1.38B; +0.90B ex-0DTE)** is the dominant magnet. Then **755 (+0.66B)**, 770 (+0.60B), 775 (+0.79B), 800 (+0.79B).
  - **Put nodes:** 740 (−0.39B), 730 (−0.31B), 744 (−0.19B), 700 (−0.58B). Ex-0DTE there's a small **757 put node (−0.17B)** right at spot.
  - **Sign changes:** 753/754 and 757/758, plus 749. Cumulative flip: 760 (all) / 770 (ex-0DTE).
- **QQQ** (spot ~688.1):
  - **Net GEX:** **+1.23B** all, **+0.34B** ex-0DTE (up from −0.9B Tuesday morning).
  - **Call walls:** **700 (+0.72B)**, 710 (+0.39B), 720 (+0.37B), 705 (+0.32B), 695 (+0.30B).
  - **Put nodes:** **670 (−0.57B)**, 650 (−0.55B), 675 (−0.29B), 660 (−0.26B).
  - **Sign changes:** **685/686**, **690/691**, 680–683, 676.
- **IWM** (spot ~282.8):
  - **Net GEX:** **+0.05B** all, **−0.12B** ex-0DTE. Flat to slightly short.
  - **Calls:** **283 (+0.15B)**, 284 (+0.10B), 285, 300 (+0.15B).
  - **Puts:** **280 (−0.14B)**, 270, 275, 278.
  - **Sign change:** **281**.
- **Dark pool this morning:** prints are small (≤$0.007B per level).
  - SPY: **754.7–754.96** and 756.5–757.0.
  - QQQ: **684.1–684.5**, 685.6 and 687.2–688.2.
  - IWM: 281.8 and 282.3–282.9.
- **9,000+ pre-market prints (Nov 11):** **none** as of 7:48. The study shows no big prints doesn't mean calm.
- **9,000+ prints from the prior session (Tue Nov 10, 165 rows; structure read):**
  - **SPY:** at 14:29, Dec 18 **775C 20k at the ask** ($8.8M) paired with Dec 800C 20k mid, both flagged closing: an upside call spread being adjusted or closed.
  - **QQQ:** at 13:24, Dec 18 **680C 10k at the ask** ($17.6M) / 715C 10k at the bid, flagged closing: a call-spread unwind.
  - **IWM:**
    - 10:57, Nov 27 **275P (~28k total) above the ask, opening, vs 267P closing**: puts rolled up.
    - 14:54, Nov 20/Dec 18 **285C 20k calendar** (sold Nov at the bid, bought Dec at the ask, both opening).
    - 15:43, Jan 270P/240P 10k closing.
  - **NVDA (41 prints, the biggest name):**
    - Jan 140P **100k above the ask, opening** vs 100P closing (tail hedge rolled up).
    - Feb 165P 75k at the bid, closing (in-the-money).
    - Call roll-downs into **185C** opening at the ask: Dec 50k, Mar 35k, Feb 50.5k, against 180/195C closing.
    - Mar 185P sold below the bid (deep ITM, closing).
  - **MSFT:** Feb 595C 20.4k at the ask, opening.
  - **VIX:** Nov 18 25C 28k sold at the bid; Nov 18 18.5P 19k at the ask.
  - **Read:** there's **no heavy index put-selling at the bid**, so this isn't the clean snap-back template. It's hedges rolled and index call spreads closed, plus **fresh NVDA 185 calls bought at the ask into the dip**, which today's chip rebound is validating so far. Upside vol is being sold (VIX 25C) and VIX puts bought: a vol-compression lean that fits today's long-gamma book.
- **History match** (`/workspace/history`): the deepest negative-gamma readings (Jul 29, Jun 10) were followed by sharp snap-back rallies on a catalyst. Last night's deep short gamma (SPY ~−5B ex-0DTE) and a catalyst (CRWV) gapping NQ +2% fits that pattern. Once the book flips long gamma, follow-through usually slows into the walls (SPY 760, QQQ 695–700).

## Combined levels map (PM range 4:00 AM to ~7:48 AM ET; it can still change before 9:30)
**Prior RTH (Tue Nov 10):**

| | High | Low | Close |
|---|---|---|---|
| SPY | 752.11 | 744.90 | 749.94 |
| QQQ | 680.80 | 667.08 | 674.81 |
| IWM | 281.30 | 277.92 | 280.56 |

Futures equivalents use current ratios (ES ≈ 10.058× SPY, NQ ≈ 41.256× QQQ, RTY ≈ 10.085× IWM) and are **approximate**.

**SPY** (PM last **756.83** @ 7:48, **gapping above the PDH**)
- **Prior day:** PDH **752.11** (ES ~7565), PDL **744.90** (ES ~7493), PDC 749.94 (ES ~7543).
- **Pre-market:** PMH **757.00** @ 6:55 (ES ~7614; ONH 7615.75), PML **753.98** @ 4:00 (ES ~7584).
- **15-min zones:** the next untested rejections are **768.7–769.2** (Nov 4), then 775.6. There's no untested support pivot below within 3%.
- **2-min EMAs (13/48/200):** **756.76 / 756.46 / 754.36**, a **bullish stack**.
- **Confluence:**
  - **757–758 (ES ~7614–7624): PMH, the ES ONH, the 757/758 sign change, the 757 ex-0DTE put node, and dark-pool prints at 757.0. The first lid.**
  - **760 (ES ~7644): the biggest call wall (+1.38B) and the cumulative flip. The main magnet and likely pin/ceiling.**
  - **754–755 (ES ~7584–7594): the PML, the 755 call node (+0.66B), the 753/754 sign change and the 754.7–754.96 dark-pool cluster. The shelf.**
  - **752.1 (ES ~7565): the PDH (gap fill/retest level).** Below that, 749 (sign change) and the 749.94 PDC.
- **Game plan:** Break and hold **757** on a 15-min close, and calls toward **760** (call wall), then 768.7–770. Lose **754** and puts toward the **752.1** PDH retest, then **749–750**.

**QQQ** (PM last **688.05** @ 7:48, **gapping above the PDH**)
- **Prior day:** PDH **680.80** (NQ ~28087), PDL **667.08** (NQ ~27521), PDC 674.81 (NQ ~27840).
- **Pre-market:** PMH **688.32** @ 7:42 (NQ ~28398; ONH 28393.5), PML **685.53** @ 5:20 (NQ ~28283).
- **15-min zones:** **695.38** untested rejection (Nov 4), then 696.8–697.1 and 701.45. Untested supports: **671.0–671.4** and 668.6 (Nov 10).
- **2-min EMAs:** **687.95 / 687.21 / 681.87**, a **bullish stack**.
- **Confluence:**
  - **690–691 (NQ ~28467–28508):** sign change just above the PMH. The first test.
  - **695–695.4 (NQ ~28673–28689): the 695 call node and the untested 15-min rejection. The key upside level.** **700 (NQ ~28880)** is the biggest call wall behind it.
  - **684–686 (NQ ~28224–28300): PML, the 685/686 sign change and the 684.1–685.6 dark-pool prints. The shelf.**
  - **680.8–681.4 (NQ ~28087–28112):** the PDH, the 680/681 sign change and the 200-day MA (~681.42, per an X News story). This is the big retest level; QQQ has closed under its 200-day four straight days.
- **Game plan:** Break **688.3** and calls toward **690–691**, then **695** (call node / untested rejection). Lose **685.5** and puts toward **681–680.8** (PDH / 200-day retest).

**IWM** (PM last **282.80** @ 7:48, **above the PDH**)
- **Prior day:** PDH **281.30** (RTY ~2837), PDL **277.92** (RTY ~2803), PDC 280.56 (RTY ~2829).
- **Pre-market:** PMH **282.87** @ 7:39 (RTY ~2853; ONH 2852.5), PML **281.51** @ 4:03 (RTY ~2839).
- **15-min zones:**
  - Untested rejections: **283.71 / 283.79** (Nov 9), then 284.69 (Nov 5) and 286.17 (Nov 4).
  - Untested supports: **279.6–279.96** (Nov 10).
- **2-min EMAs:** **282.76 / 282.61 / 281.76**, a **bullish stack**.
- **Confluence:**
  - **283–283.8 (RTY ~2854–2862): the 283/284 call nodes, the untested rejections and the Nov 9 high. The lid.**
  - **281.3–281.5 (RTY ~2837–2839): PDH, PML and the 281 sign change. The shelf.**
  - **279.6–280 (RTY ~2821–2824):** the 280 put node and the untested 15-min supports.
- **Game plan:** Break **283.8** and calls toward **284.7**, then 285–286. Lose **281.3** and puts toward **280–279.6**.

**Bias framing (Team2):**
- All three are **opening above yesterday's highs**. The play is **break-and-retest of the PDH** (SPY 752.1 / QQQ 680.8 / IWM 281.3) as support, or a failed gap that loses the PML and fills back into yesterday's range.
- The pre-market ranges are no-trade zones: SPY 754.0–757.0, QQQ 685.5–688.3, IWM 281.5–282.9.
- Wait for a **15-min body close** beyond a level, and **nothing before 9:45**.
- Casey last night: "When everything aligns for a trade inside the pre market range I'm fine with taking it. Just make sure there's some room to the next level." That's a softer line than his usual. He also posted a "trifecta trade" breakdown: a reaction at a level, then confirmation. There's no Wednesday game plan from him as of ~7:50.

## Macro
**Calendar (ET):**
- **Veterans Day:** bond market closed, stocks open. **No major US data releases.**
- Already out: MBA mortgage applications **+6.2%** (prior −1.2%), 30-yr mortgage rate 7.21% (prior 7.30%) at 7:00. German final CPI was 2.8% y/y, in line.
- Fed speakers: Bowman and Paulson spoke last night (Bowman: "still work to do" on inflation; she flagged the risk of a large equity correction if AI investment underdelivers). I found no US-session Fed speakers scheduled today.
- **Thu:** 8:30 jobless claims (consensus 195k), Barr and Hammack, 30-yr auction 13:00, then **CSCO, AMAT and Cerebras after the close** (NBIS before the open), and NY Fed's Williams in the evening.
- **Fri 8:30:** PPI.
- **NVDA earnings Nov 17**, monthly OPEX Nov 20, FOMC Dec 9 (a December hike is widely priced after Tuesday's hot CPI).

**Earnings:**
- **Before the open today:** nothing major (Yahoo: "a quiet day on the earnings and economic data front").
- **Last night:**
  - **CRWV +16%** to ~56.70. Q3 beat, 2026 revenue guide raised to $13–13.3B, adjusted profitability expected in 1H 2028.
  - RGTI +3.7% (it was −7.8% after hours).
- **Index movers pre-market** (Yahoo ~7:45):
  - Up: **NVDA +4.0%** (175.71), **AMD +6.3%**, **AVGO +4.3%**, TSLA +1.8%, META +1.2%, GOOGL +1.1%, MSFT +0.5%, AMZN +0.1%.
  - **AAPL −0.6%** is the lone mega-cap red.
  - Reuters also reports MRVL +8%, MU +6.8%.

**Financial Juice / X overnight (ET):**
- **NVDA crosscurrents:**
  - **Baird downgraded it to neutral, PT cut to $200 from $500** (6:47), and **Morgan Stanley removed it as a top pick** (keeps overweight; 7:09). The stock is still up ~4%.
  - CNBC: Nvidia's board has hired Wachtell Lipton to investigate CEO Huang over the spy-allegation story; NVDA lost ~$430B over the last two sessions.
- **Anthropic** disclosed $10B+ in new deals (The Information, 7:05). Its IPO is targeting up to a $1.4T valuation.
- **Iran:**
  - IRGC claims two tankers hit mines in Hormuz overnight (5:18).
  - **"We won't remove enriched nuclear [material] from the country"** (Mayadeen, 4:14), which pushes back on Tuesday's Al Hadath report that Iran had agreed to US demands.
  - Iran warns a US attack would trigger strikes on distant US bases (4:26).
  - Oil is bid: WTI +1.6%, Brent +2.2%.
- **Russia/Ukraine:** the Abu Dhabi trilateral talks' second day produced a major POW-swap agreement. Kushner says Europeans need to be at the table; Witkoff and Kushner plan to meet Zelenskyy in Dublin after Moscow.
- **ECB:** Makhlouf says upside inflation risks remain; Nagel says the German recovery is stronger than forecast.

**Overnight / Globex** (Yahoo, ~7:35–7:39, vs prior close):

| | Last | Prior | % | ONH | ONL |
|---|---|---|---|---|---|
| NQ | 28386.50 | 27835.25 | +1.98% | 28393.50 (7:00) | 27856.00 (Tue 18:10) |
| ES | 7612.50 | 7544.25 | +0.90% | 7615.75 (6:55) | 7549.25 (Tue 18:10) |
| RTY | 2852.00 | 2828.90 | +0.82% | 2852.50 (7:35) | 2830.20 (Tue 18:10) |

The futures ran from the 6 PM open lows and are **pressing their overnight highs**. That leaves a large gap over yesterday's ranges: ES PDH ~7565, NQ PDH ~28087, RTY ~2837. Last night's Baltics airspace scare didn't move the tape.

**Global:**
- **Asia:** Nikkei **+1.3%**, **KOSPI +2.6%**, Taiwan +3.6% (Reuters), Shanghai +0.5%, **HSI −1.0%**.
- **Europe** (~7:30): STOXX50 +0.65%, DAX +0.73%, FTSE +0.39%, CAC +0.32%.

**Cross-asset:**
- **VIX:** **18.48** (−0.98, −5.0%; overnight 18.43–18.96).
- **10-year:** cash Treasuries are closed today. The last print was **4.98%** at Tuesday's close; it briefly topped 5% after CPI.
- **Dollar:** DXY **102.54** (+0.3%).
- **Oil:** WTI **87.39 (+1.6%)**, Brent **93.46 (+2.2%)**.
- **Gold:** **4051.3 (+0.5%)**.

## Takeaway (information, not advice)
CoreWeave flipped the AI tape overnight, and dealers flipped with it. **SPY is now long ~3.5B gamma ex-0DTE** (from about −5B), and QQQ is modestly long. That favors pinning toward the walls rather than the trend-day whipsaws of earlier this week, and it fits the history-file pattern of deep negative gamma plus a catalyst producing a snap-back. The confluence levels that matter most:
- **SPY 760** (largest call wall; ES ~7644) is the magnet/ceiling. **757** (PMH / ONH / sign change) is the first lid, and **754–755** (PML / 755 call node / dark pool; ES ~7584–7594) is the shelf. The **752.1 PDH** is the gap retest.
- **QQQ 695–695.4** (call node + untested rejection; NQ ~28675–28690), with **700** behind it. The shelf is **684–686** (NQ ~28225–28300), and **680.8–681.4** (PDH + 200-day; NQ ~28087–28112) is the deeper retest.
- **IWM 283–283.8** (call nodes + untested rejections; RTY ~2854–2862) is the lid, and **281.3–281.5** (PDH / PML / 281 sign change) is the shelf.

**Gap risks:**
- The opening print is far above yesterday's ranges.
- There are two sell-side NVDA downgrades into the bounce, Iran headlines are pushing oil up, and bond-market liquidity is missing.

The cleaner read comes from the 9:45+ 15-min closes: a hold above the PML shelves keeps the walls in play, while losing them opens the PDH gap-fill retests.
