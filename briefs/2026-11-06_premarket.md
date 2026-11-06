# Pre-Market Brief, Fri Nov 6, 2026 (data as of ~8:17 AM ET)

**NFP Friday after the AI flush.** Thursday was the worst equity day since the Apr 2025 Liberation Day-type session (Nasdaq −6.4%, QQQ −6.5%, VIX spiked to 28.09). Overnight Asia extended the wipeout (Nikkei −6.0%, KOSPI −6.0%); Europe is still red but off the lows. US futures are mixed into the 8:30 print: **NQ +1.3%** (chips bounce), **ES flat/+0.1%**, **YM −1.0%**, **RTY flat**. Spot into the data: ES ~7389, NQ ~27099, RTY ~2739 (Yahoo 1m, ~8:07). VIX ~27.4. **Today is Friday (Team2 trades lightly) and weekly options expiration; monthly OPEX is Nov 20.** NFP / unemployment / AHE hit at **8:30 ET** — this brief is pre-print.

Sources: Quant Data API on the user's account (GEX by strike, dark pool, 9k+ unconsolidated flow), Yahoo Finance 1m/2m/daily, Close & Open / Forex Factory calendars, X market accounts (DeItaone, zerohedge, FirstSquawk, LiveSquawk, Team2Trading), Newsquawk / Benzinga / Investing.com for earnings and overnight tape. Financial Juice's public page did not return usable headlines this run; overnight tape is from Newsquawk/X instead.

## Positioning (Quant Data API, session date Nov 6, ~8:15 AM ET)
Pre-market GEX is a thin first read after Thursday's 0DTE put load expired. Thursday close (ex-0DTE) was SPY **−11.65B**, QQQ **−5.77B**, IWM **−4.56B**. This morning's book is still **negative gamma**, but much less deep — especially QQQ and IWM.

- **SPY** (spot ~734.5):
  - **Net GEX:** **−5.22B** all expirations / **−3.82B ex-0DTE**. Still short gamma; no cumulative flip in the near band.
  - **Put walls (largest):** **725 (−1.39B)**, **730 (−1.15B)**, 720 (−0.82), **700 (−0.77)**, **735 (−0.73)**.
  - **Call residue (far above):** 780 (+0.23), 775 (+0.23), 760 (+0.19), 770 (+0.16) — not magnets near spot.
  - **Sign changes near spot:** **736 / 738 / 739 / 741–742 / 750**.
  - **Dark pool (Nov 5):** the old **766.43 ($8.7B)** is still listed but sits at Wednesday's price outside Thursday's range — late prior-session flow, ignore as today's level. **In-range magnet is the 733.00–733.08 cluster (~$8.8B combined across buckets)**, right on the PDL/PDC.
- **QQQ** (spot ~657):
  - **Net GEX:** **−0.89B** all / **−0.84B ex-0DTE** (was −5.77B at Thursday's close). Still negative, but the flush of 0DTE puts left a much thinner short-gamma book.
  - **Put walls:** **650 (−0.75B, largest)**, 640 (−0.40), 630 (−0.28), 625, 645.
  - **Call nodes:** **700 (+0.32)**, **670 (+0.21)**, 690 (+0.14).
  - **Sign changes near spot:** **654 / 656 / 657 / 658 / 660–661**.
  - **Dark pool (Nov 5):** old 691.73 ($4.83B) is above Thursday's range (late prior). **In-range: 647.04 ($1.53B)** plus 647.7 buckets — pinned on yesterday's low.
- **IWM** (spot ~271.6):
  - **Net GEX:** **−0.28B** all / **−0.01B ex-0DTE** (basically flat ex-today). Softest short-gamma of the three.
  - **Puts:** **275 (−0.21)**, 260 (−0.16), **270 (−0.07)**. **Calls:** 285 (+0.06).
  - **Sign changes:** 266, **272 / 272.5 / 274–276**.
  - **Dark pool:** old 283.94 ($0.38B) overhead; in-range **270.98 ($0.08B)** and 271.67.
- **9,000+ pre-market (Nov 6):** **none** as of the pull. Lack of big prints does not mean calm into NFP.
- **9,000+ Thursday (Nov 5, 270 rows via API):** structure read, not Quant Data labels. Same-timestamp multi-leg groups treated as spreads/rolls; deep-ITM near-expiry sales as likely closing.
  - **SPY:** **11:54** bought Nov 27 **730/700 put spread** 22.2k (730P ask opening, ~$21M on that leg) — fresh downside mid-dump. **15:32** Nov 9 **725/710 put spread** 33.4k above ask, both opening — near-dated puts into NFP. **15:29** sold Nov 20 far-OTM puts at the bid (620P 75k / 500P 150k / 380P 75k) — tail supply / closing, not a bounce signal. Late **16:11** deep-ITM Nov 20 790/785P pair (~10k) — structure/closing.
  - **QQQ:** **14:26** and **16:13** Nov 20 **750P** 10.7k then 22.1k at the ask, deep ITM ($105M / $228M) — structure/roll, not naked directional. **13:32** Nov 30 **675P** 10k at ask ($34M). Short-dated Nov 6 ITM puts traded into the close (715/717P 10k) — expire today. **12:24** Dec 630P 10.5k at bid.
  - **IWM:** put-spread supply rolled down (Nov 20 270/267, 267/264, 264/261; into the close **261/259P 24k at the bid**).
  - **VIX:** call-heavy — Dec/Nov 21–25C rolls and blocks while spot was 25–27; monetizing/rolling the vol bid more than fresh panic at the highs alone.
  - **NVDA / semis:** Mar 2027 **210/230 call spread** 29.5k into the hole ($36M on 210C); large Jan/May 150P structures both ways and overnight EXT_HOURS put blocks — mixed LEAPs, not a clean sweep-reversal.
  - **Read:** Thursday was **trend continuation in deep negative gamma**, not the study's snap-back template. Heavy put selling at the bid did appear (SPY far-OTM 15:29, some QQQ tails) but *during* the flush and alongside fresh near-dated put buying into NFP (SPY Nov 9 725/710, QQQ short-dated). Hedges were rolled down and out, not abandoned. This morning's thinner book (−5.2B / −0.9B / flat) is less extreme than Jun 10 (−15.5B) or Jul 29 (−22.9B) snap-back precedents in `/workspace/history/gex_before_moves.md`, and the catalyst today is NFP, not a washout low with abandoned puts.

## Combined levels map (PM range 4:10 AM–~8:17 AM ET; can still change before 9:30)
Prior RTH (Thu Nov 5): SPY H/L/C **765.97 / 732.71 / 733.25**; QQQ **683.64 / 647.27 / 648.06**; IWM **284.69 / 270.52 / 271.07**. Ratios ~ES 10.06× SPY, NQ 41.24× QQQ, RTY 10.08× IWM — futures levels approximate.

**SPY** (PM last **734.62** @ 8:17 — just above the PDL, inside Thursday's range)
- PDH **765.97** (ES ~7704), PDL **732.71** (ES ~7370), PDC **733.25** (ES ~7375).
- PMH **738.03** @ 4:36 (ES ~7424; ONH 7427.25), PML **733.50** @ 8:12 (ES ~7378; ONL 7322.25).
- 15-min zones: Thursday's entire dump left almost no untested support inside the day — next referenced shelves are the **725 / 730** put walls, then **700**. Overhead untested since the open: **756–762** (old put/floor zone from Wed), then **765–770** (Thu PDH / Wed world).
- 2-min 13/48/200 EMAs @ 8:16: **734.36 / 734.90 / 735.33** — tightly stacked, mild bearish tilt, **chop**.
- Confluence:
  - **732.7–735:** PDL, PDC, PML, the **733 dark-pool cluster (~$8.8B)**, put wall **735**, and spot (ES ~7370–7390). **Best confluence on SPY — the shelf under the open.**
  - **736–738:** sign changes + PMH (ES ~7410–7424). First upside lid inside the PM range.
  - **725–730:** next put walls (ES ~7290–7340).
- Game plan: Break **738** and calls toward **750** (sign) then **760**; lose **732.7** and puts toward **730 / 725** (GEX walls).

**QQQ** (PM last **657.11** @ 8:17 — **reclaimed the PDL**, trading mid-Thursday range; chips leading)
- PDH **683.64** (NQ ~28195), PDL **647.27** (NQ ~26700), PDC **648.06** (NQ ~26735).
- PMH **660.35** @ 4:36 (NQ ~27235; ONH 27251.5), PML **647.05** @ 8:09 (NQ ~26690; ONL 26366.5 — NQ swept well below the cash PDL overnight then recovered).
- 15-min zones: **650** put wall; **670** call node; old **680** wall / Mon low now resistance; **683–689** Thursday lid.
- EMAs @ 8:16: **656.85 / 657.31 / 655.58** — 13 under 48 but both above 200; recovering / not a clean fan.
- Confluence:
  - **647–650:** PDL, PML, **647.04 dark pool ($1.53B)**, **650 put wall** (NQ ~26690–26800). **Floor and best downside confluence.**
  - **654–661:** sign changes + spot + PMH (NQ ~26980–27235). **Intraday magnet / lid of the bounce.**
  - **670:** call node (NQ ~27630) — first real upside GEX target if 661 gives.
- Game plan: Break **660.4** and calls toward **670** (GEX) then **680**; lose **650** and puts toward **640** (next put wall).

**IWM** (PM last **271.67** @ 8:16 — pinned on the PDL inside a tight PM range)
- PDH **284.69** (RTY ~2870), PDL **270.52** (RTY ~2727), PDC **271.07** (RTY ~2732).
- PMH **272.20** @ 7:26 (RTY ~2743; ONH 2746), PML **270.92** @ 6:09 (RTY ~2731; ONL 2714).
- 15-min zones: **275** put wall overhead; **265 / 260** below; **282–284** (Thu pivot / old sign) far above.
- EMAs @ 8:16: **271.60 / 271.55 / 271.51** — fully bunched, **pure chop**.
- Confluence:
  - **270.5–272.2:** PDL, PDC, entire PM range, 270 put residue, DP 270.98 (RTY ~2727–2743). **The whole tape is the confluence.**
  - **275:** largest put wall / sign cluster (RTY ~2770).
- Game plan: Break **272.2** and calls toward **275** (put wall flip / sign); lose **270.5** and puts toward **265 / 260**.

Bias framing (Team2):
- All three open **inside Thursday's range** (QQQ reclaimed PDL overnight; SPY/IWM hug it). Pre-market ranges are no-trade zones (SPY 733.5–738.0, QQQ 647.1–660.4, IWM 270.9–272.2).
- Opening near/above the PDL keeps that level as **support to defend**; a failed hold and 15-min close back under PDL flips it to resistance (classic Team2 short).
- Watch rejection vs break-and-retest at PMH for the first directional tell after data. Wait for a **15-min body close** beyond a level; **nothing before 9:45**. Friday = size down / victory-lap day per Casey.

## Macro
**Calendar (ET):**
- **8:30 NFP (Oct):** forecast **65K**, prior **29K**
- **8:30 Unemployment:** forecast **4.2%**, prior **4.2%**
- **8:30 AHE m/m:** forecast **+0.3%**, prior **+0.1%** (the inflation hinge for Dec hike odds)
- **8:30 Canada** employment / unemployment (14.6K / 6.5%)
- **9:10** Musalem moderated discussion
- **10:00** UMich prelim sentiment (forecast ~48–48.1; inflation expectations prior 4.7%)
- **12:15** Bowman; **13:00** Daly (CNBC); **15:00** consumer credit (~$12–13.4B vs $8.3B)
- Williams spoke ~4:30 AM (ECB event)

**Earnings:** ABNB beat (EPS $3.16 vs ~$2.85, rev $4.87B) — PM ~194 after AH surge from ~170 RTH. HUM beat on adj. EPS, raised FY guide — mixed PM. VST reported — PM bid (~119 vs ~114.5). CHTR BMO — soft in PM (~118 vs ~125). NET choppy PM after Thu AH. Semis leading the bounce: SMH/MU/AMD/LRCX/MRVL sharp premarket green after Thursday's −12% to −17% memory/chip wipeout (Newsquawk / DeItaone).

**Overnight / Globex:** NQ ONL **26366.5** (6:19 PM) → ONH **27251.5** (4:36 AM) — full overnight reclaim. ES ONL **7322.25** → ONH **7427.25**. YM lagged (ONL 50891 / last ~51100, −1% vs settle). Asia: Nikkei **−6.0%** (bear-market talk from June peak per ZH), KOSPI **−6.0%** (Samsung/SK Hynix), HSI **−1.3%**. Europe: STOXX **−1.6%**, DAX **−2.4%**, FTSE **−2.1%** (off worst as ASML/memory stabilize). UBS (via DeItaone): NQ rebound may be misleading — CTAs still heavy and may need to reduce.

**Cross-assets (~8:00–8:15):** VIX **~27.4** (off Thu high 28.09; still elevated). 10y **~4.84%** (−6 bp vs Wed). DXY **~102.0** (+0.5%). WTI **~90.7**, Brent **~98.3** (FirstSquawk had Brent >$100 overnight; faded). Gold **~4068** (−1.1%).

**X tape:** ZH — Nasdaq futures bounce into payrolls; Nikkei −6% / tech HF round-trip of 2026 gains. DeItaone — chip premarket surge (LRCX +9%, MU +7.5%); UBS CTA warning; ES bearish structure notes (targets 7317/7240 if 7386 fails). Team2Trading Thu: "nice work if you traded the trend" / high-vol caution, no Friday game-plan post yet as of this pull.

## Takeaway
Dealer book is still **short gamma** but much thinner than Thursday's close after 0DTE expiry — SPY **−3.8B ex-0DTE** with put shelves at **725/730/735**, QQQ **−0.8B** with the **650 put wall** as the clear magnet under the bounce, IWM basically flat. Best confluence: **SPY 732.7–735** (PDL + 733 DP + 735 put), **QQQ 647–650** (PDL/PML/DP/put wall) and **654–661** (signs + PMH), **IWM 270.5–272.2** (entire PM range on the PDL). Magnets into NFP are those put shelves under spot, not the distant call residue at 760–780 / 700. This is an **event-vol Friday**, not a clean study snap-back (put supply arrived mid-flush with fresh near-dated hedges still on). Information only, not advice — and per Team2, Fridays are for light size.
