# Pre-Market Brief, Thu Nov 5, 2026 (data as of ~8:05 AM ET)

**Rotation, part two: Dow up, Nasdaq down.** The day after the blue-wave rally, NQ has bled lower all night on a second leg of chip selling. NQ is 28,300 (-0.9%), ES 7,725.25 (+0.1%), and RTY 2,874.4 (+0.3%) vs Wednesday's settle, as of 7:54 AM ET. NQ topped at the 6:00 PM reopen (28,620.75) and bottomed at 28,167.75 at 12:52 AM. **QCOM -10.6%** (handset chips -26%), **ARM -6.7%**, AMD -4.7%, MU -4.5%, AVGO -2.5%, and NVDA -1.6% are dragging, while **APP +21.6%** stands out. KOSPI fell 5.3% on the AI-spending worries. The **BoE hiked to 4.00% in a unanimous 9-0 vote** (7-0-2 expected), and two members want more. SPY and IWM are inside Wednesday's range. **QQQ is below Wednesday's low (687.90)**, so that level is now resistance. Coming up: jobless claims 8:30, Hammack 8:50, Barkin 9:10; NFP is tomorrow. Today is Thursday, not Friday or monthly opex.

## Positioning (Quant Data API on the user's account, ~8:05 AM ET; pre-market GEX is a thin first read, so Wednesday's 4:15 PM close is shown alongside)
- **SPY:**
  - **Net GEX:** **+1.78B ex-0DTE** pre-market (+1.95B all expirations), vs Wednesday's close at **+2.82B ex-0DTE**. Wednesday's +23.8B all-expiration number came from the 768 0DTE pin, which has expired. Still **positive gamma**, the first back-to-back positive reads in this run.
  - **Call walls:** 770 (+0.87B, mostly today's expiry), 800 (+0.82B), 780, 775-776, 810.
  - **Put strikes:** 764 (-0.57B) and 762 (-0.38B), both mostly 0DTE; then 757 (-0.23B ex-0DTE), 735, 725.
  - **Sign changes:** at spot, **766-769**; at Wednesday's close they were 765 and 772-773. The cumulative flip is up at 785 (802 ex-0DTE at the close).
  - **Dark pool (Nov 4):** **766.43 ($1.38B)**, 766.81 ($0.62B), and about $10B combined across the 766.5-768.5 50-cent buckets. The listed 754.51 ($5.05B) is at Tuesday's closing price, outside Wednesday's range, so it's likely a late-reported Tuesday trade. Don't treat it as Wednesday's level.
- **QQQ:**
  - **Net GEX:** **-3.29B ex-0DTE** (-3.78B all), vs Wednesday's close at -5.78B ex-0DTE. Still **negative gamma**.
  - **Put walls:** **680 (-1.33B, largest)**, 675 (-0.73B), 685 (-0.54B), 691 (-0.51B), 670.
  - **Call gamma is small:** 705 (+0.30B), 710, 715, 720.
  - **Sign changes:** **687-688**, then 692-694. There's no cumulative flip in range, so the whole near book is short gamma.
  - **Dark pool:** **685.49 ($3.19B)**, also at Tuesday's close and likely late-reported, but it sits right at today's spot. Then 691.5-692 (~$3.6B in buckets; 691.71 alone is $0.84B), 693.15 ($0.50B), 695.5.
- **IWM:**
  - **Net GEX:** about **-0.14B ex-0DTE**, basically flat (close -0.58B).
  - **Call strikes:** 290 (+0.21B), 286-287, 285.
  - **Put strikes:** 260, 270, 280 (-0.12B).
  - **Sign changes:** **282-284**; it was 281 at the close.
  - **Dark pool:** 284.0 bucket ($1.06B), 283.5 ($0.44B). The 279.51 print ($0.38B) is a likely Tuesday late print.
- **9,000+ contract prints, pre-market:** none so far (Quant Data unconsolidated flow, 0 rows for Nov 5 as of ~8:05). That doesn't mean calm.
- **9,000+ contract prints, Wednesday (239 rows, saved in /workspace/history/flow_9k_2026-11-04.csv; most are multi-leg).** The ones that matter (ET):
  - **SPY:**
    - **9:43:** bought the Nov 13 **745/730 put spread**, 55.6k at the ask (745P $1.76, opening; 730P $0.77). That's about $5.5M of fresh protection put on into the open.
    - **14:44:** sold 14.6k of the 745P at the bid ($1.35) against the 720P at the ask, so part of that hedge was taken off or rolled down.
    - **14:35:** sold the Nov 20 **757P at the bid**, 21.7k across two prints ($4.89, $10.6M), paired with the 725P at mid. That's put-spread supply under the market, likely closing (OI 30.8k).
    - **9:40:** Nov 20 728/718P, 9.5k.
  - **QQQ:**
    - **Put selling at the bid:**
      - **Nov 20 680P 22k ($8.13, $17.9M, 14:25)**, right at the put wall. OI was 93k, so likely closing or monetizing.
      - Jan 650P 10k ($11.8M, 15:02).
      - Dec 550P 20k (11:21).
      - Dec 2027 500P 23.1k, flagged opening ($28.9M, 10:04).
      - 12:14, same timestamp: sold Dec 2027 550P 10k at the bid and bought Mar 2027 550P 10k at the ask, a calendar roll shorter.
    - **Other puts:**
      - Dec 690P 21.5k at mid ($38.6M, 13:10).
      - Nov 6 680P 10k at the ask twice (11:36 and 11:38, ~$5.7M), short-dated puts bought into NFP.
      - Dec 535/515/500P 12k each at the ask (13:39), a tail structure.
    - **Calls:**
      - Nov 6 705C 23k sold at the bid, opening ($9.3M, 9:48), near Wednesday's top.
      - 14:37-14:39: Nov 20 710C 10k at the ask and Dec 710C 10k at the bid, likely a roll in.
  - **IWM:**
    - The Nov 20 271/266 and 272/266 put spreads again (~12k, 9:41-9:42; 272P opening above the ask).
    - **15:24:** rolled 30.4k from Nov 20 270P (sold at the bid) into Dec 275P (above the ask, $12.1M), rolling protection up and out.
    - Mar 235P 10k bought; Jan 245P 10k sold.
  - **Semis and other:**
    - SMH Nov 6 500P 19.7k + 10k and Nov 13 475P 19.7k at the bid (11:44-11:58).
    - VIX Nov 18 **20/30 call spread, 77k bought** (9:44); VIX 17P blocks sold. VIX Jan to Mar 70C, 30k roll.
    - HYG put structures (Nov 79/77P 30k, Dec/Jan/Jun puts).
    - XLF 2027 risk reversals 20k, some canceled.
    - TLT 2028 structures.
- **Read (structure, not labels):** Wednesday's near-dated QQQ/SPY put supply was **sold at the bid**, especially QQQ 680P at the wall and SPY 757P. That's hedge monetization after the event, the pattern that came before the study's snap-backs. It came *after* the rally, though, not at a deep-negative-GEX low, so it isn't a fresh sweep-reversal signal. At the same time, new protection was bought: SPY Nov 13 745/730, QQQ Nov 6 680P into NFP, IWM rolled up into Dec 275P, and VIX 20/30 calls. So hedges are being restructured, not abandoned. QQQ is now gapping toward that 680 wall in negative gamma. That reads more like **trend continuation in tech** (an AI/semis repricing), not a sweep reversal, unless 680-682 gets swept and reclaimed. SPY's positive gamma favors mean reversion around 765-770.
- Note: GEX by strike, dark pool, and 9k+ flow were pulled from the Quant Data API on the user's account (the key worked). I didn't walk the heatmap, interval map, net drift, and other My Pages tabs page by page this morning.

## Combined levels map (PM range 4:10 AM to ~8:05 AM ET, can still change before 9:30)
The 4:00-4:06 AM prints (SPY 763.88, QQQ 682.37, IWM 283.71) were zero-volume wicks well below where ES, NQ, and RTY were trading, so I've treated them as bad ticks and used the range from 4:10. Wednesday's SPY 775.64 print is also a known bad tick, so the PDH is 769.23. Ratios: ES ~10.07x SPY, NQ ~41.23x QQQ, RTY ~10.11x IWM. Futures levels are approximate.

**SPY** (PM last 767.46, inside Wednesday's range and the PM range)
- PDH 769.23 (ES ~7743; Wednesday's ES high 7746.25), PDL 762.64 (ES ~7677), PDC 766.81 (ES ~7719).
- PMH 768.56 at 7:04 (ES ~7736; ONH 7738.75), PML 765.70 at 4:30 (ES ~7708; ONL 7691).
- 15-min zones: Monday's high 763.86, which was retested as support Wednesday at 11:30; Tuesday's high 757.07 below; 772-775 above (untested since Wednesday's 10:00 spike).
- 2-min 13/48/200 EMAs: 767.35, 767.56, 767.39. All flat and bunched within 0.2, so no trend, a pure chop read.
- Confluence:
  - **768.5-770:** PMH, PDH 769.23, the 768-769 sign change, the 768 dark pool bucket (~$2.2B), and the **770 call wall** (ES ~7736-7751). The lid, and the best confluence on SPY.
  - **766.4-767.5:** PDC 766.81, the **766.43 dark pool ($1.38B)**, and the EMAs. The magnet inside the PM range.
  - **762.6-765.7:** PML, the 764/762 put strikes, Wednesday's 765 flip, and the PDL (ES ~7677-7708). The floor.
- Game plan: a 15-min close above 770 and calls toward 772-773 (sign changes), then 775; lose 762.6 and puts toward 757.

**QQQ** (PM last 686.44, **below the PDL**, so 687.9 is now resistance)
- PDH 701.45 (NQ ~28919; Wednesday's NQ high 28969), PDL 687.90 (NQ ~28360; Wednesday's NQ RTH low 28405), PDC 691.95 (NQ ~28527).
- PMH 689.31 at 6:54 (NQ ~28418), PML 684.79 at 4:24 (NQ ~28232). The NQ overnight low 28167.75 (12:52 AM) is roughly QQQ 683.2.
- 15-min zones: Tuesday's range 683.18-688.69, Oct 30 low 683.45, Monday's low 680.33.
- EMAs: 686.08, 687.01, 688.89. **Bearish stack** (13 under 48 under 200), with price under all of them.
- Confluence:
  - **687.9-689.3:** PDL, PMH, the 687-688 sign changes, the 200 EMA, and Tuesday's high (NQ ~28360-28418). The lid, and the best confluence on QQQ.
  - **685-685.5:** the 685 put strike and the **$3.2B 685.49 dark pool**. That's spot right now.
  - **683.2-684.8:** PML, Tuesday's low, the Oct 30 low, and the NQ overnight low (NQ ~28165-28232). The floor.
  - **680-680.3:** the **680 put wall (largest)**, Monday's low, and where Wednesday's 22k 680P were sold (NQ ~28034-28048).
- Game plan: a 15-min close back above 689.3 and calls toward 691.7-692 (PDC, dark pool), then 694; lose 683.2 and puts toward 680.3, then 675 (NQ ~27828).

**IWM** (PM last 284.29, inside Wednesday's range; the PM low is being made right now)
- PDH 286.17 (RTY ~2892), PDL 281.30 (RTY ~2843), PDC 284.02 (RTY ~2870).
- PMH 286.13 at 6:24 (RTY ~2891; ONH 2888.3), PML 284.29 at 8:06 (RTY ~2873; ONL 2864).
- 15-min zones: Monday's high 283.19, Tuesday's high 281.99, Oct 29 high 285.26.
- EMAs: 284.68, 285.06, 284.75. The 13 is under the 48 and price is below all three, a mild bearish tilt.
- Confluence:
  - **286.1-286.2:** PMH matching the PDH (a double top) plus the 286 call strike (RTY ~2891). The lid.
  - **283.7-284.4:** PML, PDC 284.02, the 284 sign change, and the **284 dark pool bucket ($1.06B)** (RTY ~2867-2874). The pivot.
  - **281.3-282:** PDL, Wednesday's 281 sign change, and Tuesday's high (RTY ~2843-2850).
- Game plan: a 15-min close above 286.2 and calls toward 287, then 290 (call wall); lose 283.7 and puts toward 282, then 281.3.

Bias framing:
- **SPY and IWM** open inside Wednesday's range. The pre-market range is a no-trade zone (SPY 765.7-768.6, IWM 284.3-286.1). For SPY, watch rejection vs a 15-min close at the 768.5-770 lid. IWM's PDH/PMH double top at 286.2 is the breakout line.
- **QQQ** opens **below its PDL**, so 687.9-689.3 is resistance. A rejection there is the continuation-short setup; a 15-min close back above is a failed breakdown. QQQ's PM no-trade zone is 684.8-689.3.
- Wait for a 15-min close beyond a level, nothing before 9:45. Claims (8:30) and the Fed speakers (8:50, 9:10) land before the open.

## Macro
- **Calendar (ET, Forex Factory; actuals from Financial Juice):**
  - 7:00 **BoE: hiked 25bp to 4.00%** as expected, but the vote was **9-0** (forecast 7-0-2; prior 3-0-6). Its guidance changed to "assess evidence at each meeting." Lombardelli, Pill, and Greene see a case for more near-term hikes, Pill saying "a single 25bp hike unlikely to be sufficient." Bailey: a further increase "may be warranted" unless there's progress on the Iran conflict. Traders now price about 50% odds of another hike in December.
  - 5:30 Challenger layoffs 43.99K (prior 43.28K).
  - **8:30 initial jobless claims** (forecast 197K, prior 194K); also prelim Q3 productivity (forecast 2.8%, prior 1.4%) and unit labor costs (forecast 0.3%, prior 1.3%). Not out yet when this was pulled.
  - 8:50 Fed's **Hammack**, 9:10 **Barkin**. 10:30 BoC's Macklem, nat-gas storage (forecast 81B, prior 80B). 1:00 PM Lagarde. 4:00 PM Canada budget.
  - Overseas: Norges Bank held at 4.5%. Eurozone PPI 11.1% y/y (forecast 10.6%). UK construction PMI 43.6 (forecast 46.5). French industrial production -0.5%.
- **Friday:** NFP 8:30 (forecast 65K, prior 29K; unemployment 4.2%; AHE +0.3% m/m, prior 0.1%). Canada jobs 8:30. UMich prelim 10:00 (forecast 48.1, prior 46.3; inflation expectations prior 4.7%). BoJ's Ueda 11:00. Yesterday's recap had Williams 4:30 AM, Musalem, and Bowman Friday (FF lists them as low impact). One X post cites CME FedWatch at about 81.5% for a December **hike**; I haven't verified that.
- **Earnings:**
  - **After Wednesday's close (pre-market % as of ~8:00, Yahoo):**
    - **QCOM -10.6%** (154.80): EPS $2.17 vs $2.16, revenue $10.32B vs $10.11B, but handset chips -26% and the guide midpoint slightly light.
    - **ARM -6.7%** (179): beat and guided in line; ACV slightly light.
    - **APP +21.6%** (330.5): EPS $4.30 vs $4.03, revenue $2.185B.
    - **MELI -8.6%**, **HUBS -8.6%** (weak guide, per X), SNAP -10.8%, COHR -2.9%, MCK -1.9%, MET -1.8%, ALL +1.5%, MSI flat.
  - **Before the open today:** TM +8.8%, PH +7.3%, SONY +5.9%, CI +3.0%, COP +1.8% (Q3 out), DUK +1.0%, CMI -4.6%; SO and APD roughly flat (stale quotes). RUN +22% on a Q3 beat.
  - **Semis pre-market:** AMD -4.7%, MU -4.5%, AVGO -2.5%, NVDA -1.6%, TSLA -2.3%. META +0.8%.
  - **After the close today:** ABNB, NET, EOG, SPG, MNST, LITE, DVN (from yesterday's recap list; not re-verified).
- **Headlines (Financial Juice, ET):**
  - **Iran/Hormuz:** IRNA says a tanker hit a mine in Hormuz this morning (5:14 AM). Oman and Iran's foreign ministers discussed securing sea routes and resuming navigation, stressing "a shift from de-escalation to lasting deals" (5:08-5:26 AM). UKMTO has an incident report near Qatar (3:20 AM). Houthi missiles toward Medina were intercepted (4:48 AM). Putin envoy Dmitriev calls reports of Russian diesel tankers turning away from the US "fake" (7:46 AM).
  - **Chips:** about 600,000 Nvidia H200s are in Hong Kong awaiting shipment to mainland China (6:28 AM). Micron paused its $4.5B Taiwan plant after a labor row (3:55 AM).
  - **Other:** Visa forecasts the strongest US holiday sales growth since 2021 (7:11 AM). The Binance hack led US regulators to check bank systems (5:21 AM). China is keeping anti-subsidy duties on some US imports for 5 years (4:09 AM). South Korea is weighing buying long-term Treasuries (4:06 AM). ECB's Zigman sees a "rather big chance" of a December hike (5:16 AM).
  - The RSS pull only reaches back to about 2:40 AM.
- **X market news:** the common read is "the rally is splitting": Dow futures about +0.5%, S&P flat, Nasdaq-100 about -0.5 to -0.9%. Semis and memory are getting repriced (QCOM, ARM, MU, SNDK, STX, LITE red) on AI-capex and data-center regulation worries after the Democratic sweep. Solar, China ADRs, and banks lead (RUN +16-22%). Small caps and breadth are holding. One post put CNN Fear & Greed at 27.
- **Globex (Yahoo, 7:54 AM ET, vs Wednesday's Yahoo daily close):**
  - NQ 28,300 (-0.9% vs 28,566.75), overnight range 28,167.75-28,620.75. High at the 6:00 PM open, low 12:52 AM, a 4 AM+ high of 28,465.
  - ES 7,725.25 (+0.1% vs 7,720.50), 7,691-7,738.75 (high 7:04 AM).
  - RTY 2,874.4 (+0.3% vs 2,865.9), 2,864-2,888.3 (high 6:24 AM).
  - NQ is gapping below Wednesday's RTH low (~28,405); ES and RTY are inside Wednesday's range.
- **Global:**
  - **Asia:** Nikkei 61,078 (-1.8%), **KOSPI 5,384 (-5.3%)**, Hang Seng 24,797 (+3.7%), Shanghai 3,690 (+0.1%). X posts cite Taiwan at -3.2%; I didn't pull it.
  - **Europe:** Stoxx 50 6,300 (+0.5%), DAX 26,579 (+0.5%), FTSE 10,911 (+0.8%), CAC 8,256 (+1.0%).
- **Vol and cross-asset:**
  - VIX 16.92 (Wednesday close 16.6-16.8; overnight 16.70-17.19).
  - 10-year 4.89% (Wednesday close; live not pulled, though X posts cite 4.86-4.88%).
  - DXY 101.60 (+0.1%). WTI 89.43 (+1.5% vs the 88.12 settle; overnight 86.65-89.84). Gold 4,130 (+1.4%, overnight high 4,155.8).

## History
- **SPY:** positive ex-0DTE gamma (+2.8B close, +1.8B now) usually means mean reversion. The study's caveat is that positive gamma with walls above spot (Jun 22 +12.4B, Oct 13 +26.6B) still saw 1%+ drops, so the 770 wall caps rallies but doesn't guarantee a floor.
- **QQQ:** still in negative gamma (-5.8B at the close), the zone where most of the study's big moves started.
- **Flow:** the snap-back marker (heavy put selling at the bid at a deep-negative low, Jun 10-11, Jul 28-30) showed up Wednesday *after* the move, not at a low. The short-dated QQQ Nov 6 680P bought into Friday's NFP fits the study's "short-dated puts bought into an event, then a whipsaw" pattern.

## Takeaway (information, not advice)
The magnets that matter:
- **SPY:** 768.5-770 (PMH, PDH, sign change, 770 call wall) is the lid; 766.4-767.5 (PDC plus the $1.4B dark pool) is the magnet; 762.6-765.7 is the floor. Positive gamma means chop inside that until a 15-min close breaks out.
- **QQQ:** the weak one again. It's under its PDL with a bearish EMA stack and short gamma. 687.9-689.3 is the lid (PDL, PMH, sign change, 200 EMA). 683.2-684.8 is the floor, then the **680 put wall**, where moves can extend.
- **IWM:** 286.2 (PDH/PMH double top) is the breakout line; 283.7-284.4 (PML, PDC, sign change, dark pool) is the pivot.

Watch whether semis keep diverging from the Dow and small caps after claims and the Fed speakers. Let the 15-minute close after 9:45 decide.
