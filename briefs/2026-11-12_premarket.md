# Pre-Market Brief, Thu Nov 12, 2026 (data as of ~7:50 AM ET)

**Risk-off in tech on the Nvidia CEO crisis.** As of 7:35 ET (Yahoo): **NQ 28207 (−0.94%)**, **ES 7610.5 (−0.39%)**, **RTY 2851.1 (−0.09%)**. **NVDA is −7.9% pre-market (160.00)** after the WSJ reported the board met Wednesday night on whether to oust Jensen Huang, and the NYT reported a second affair with a direct report (CNBC, NBC). No board outcome announced yet, so a headline can hit at any time. Bernstein and Baird cut targets to $200; Morgan Stanley pulled it from Top Pick. CRWV −9.9%; AMD +1.7%, AVGO +0.8% are holding up. **Dealers flipped back to short gamma in SPY and QQQ**, so moves can extend rather than pin. **QQQ is trading below yesterday's low (683.64)**, which makes the PDL resistance. VIX 18.34 (+4.9%).

**What's different today:** bond market reopens after Veterans Day (10-yr last ~5.00%). **8:30 jobless claims** (consensus 194k, prior 189k; Investing.com). Not a Friday, not monthly OPEX (Nov 20).

**Sources:** the Quant Data API on the user's account (GEX by strike, dark pool, 9k+ unconsolidated flow; pulled 7:48 ET), Yahoo Finance (1m/2m/15m bars, futures, global, cross-asset), Financial Juice RSS, X (Team2Trading, X News), CNBC, NBC, Yahoo, IBD, Euronews, Investing.com. **Caveats:** positioning came from the Quant Data API, not the browser My Pages tabs (not checked this run, so the 'contract flow' Session Date was not touched). "Magnets" means the largest GEX strike nodes plus dark-pool clusters. Prior-session 9k+ flow is from last night's close pull.

## Positioning (Quant Data, 7:48 AM)
**Regime flip:** SPY went from +3.55B ex-0DTE at last night's close to **−0.95B**; QQQ from −0.10B to **−1.95B**; IWM −0.67B to **−0.41B**. All three are short gamma: expect less pinning, more trend/whipsaw.

- **SPY** (spot ~756.4): net GEX **−2.47B** all / **−0.95B** ex-0DTE.
  - Call walls: **775 (+0.82B)** biggest, 770 (+0.61B), 765 (+0.53B ex / +0.72B all), 763 (+0.19B).
  - Put nodes: **757 (−0.40B ex / −0.54B all) right above spot**, **756 (−0.71B all, mostly 0DTE)**, **750 (−0.53B ex / −0.72B all)**, 753 (−0.40B all), 740, 730, 700 (−0.57B).
  - Sign changes: **754/755**, **759–761** (all), **762** (ex-0DTE). No cumulative flip near spot.
- **QQQ** (spot ~683.3): net GEX **−2.60B** all / **−1.95B** ex-0DTE.
  - Calls: **700 (+0.58B)**, 725 (+0.42B), 705, 720.
  - Puts: **680 (−0.69B ex / −0.79B all)** the biggest, **690 (−0.59B)**, 685 (−0.46B all), 675, 670, 650 (−0.59B).
  - Sign change: **693**.
- **IWM** (spot ~282.65): net GEX **−0.34B** all / **−0.41B** ex-0DTE.
  - Calls: 290, 286, 287, 285 (all small, ≤0.07B).
  - Puts: **270 (−0.13B)**, 272, 268, **279 (−0.07B)**, 282 (−0.07B all).
  - Sign change: **284/285**.
- **Dark pool this morning (small prints):** SPY **756.65** (cluster 756.2–756.7); QQQ **683.8–684.0** and **686.0**; IWM 282.8–282.9.
- **9,000+ pre-market prints (Nov 12):** **none** as of 7:48. Per the study, no big prints doesn't mean calm.
- **9,000+ prints, prior session (Wed Nov 11, 150 rows; structure read):**
  - **SPY:** 12:40 Dec 18 810C 110.6k closed at the bid, rolled into Dec 4 800C 27.8k (opening) and **Dec 4 775C 22.3k at the ask ($10.5M, opening)**; 12:36 Nov 27 775C/800C 55.6k call spread sold into the highs; 12:13 Dec 31 put hedges rolled up (745P bought at the ask); 10:11 Feb 670P 14k sold at the bid, opening.
  - **QQQ:** **10:11 Dec 31 650P 10k above the ask, opening ($11.2M)**; 12:09 Dec 744C 10k at the ask.
  - **IWM:** Jan hedges closed. **VIX:** 22 prints, all closing.
  - **Single names:** AMD Feb 590C→650C roll-up 12.5k ($119M); MSFT calls rolled down to Feb 570C 23.8k; NVDA Mar 150P 10k closed at the bid (15:56), before the after-hours drop.
  - **Read:** mostly hedges closed and calls rolled into strength, not the at-the-bid put selling that preceded past snap-backs. With the overnight gap down, Wednesday's flow looks like positioning for continuation that got caught by a headline, not a sweep-reversal signal.

## Combined levels map (Team2 layer + GEX)
PMH/PML are 4:00 AM to ~7:48 ET and can still change before 9:30. Futures equivalents use 7:35 ratios (ES ≈ 10.06× SPY, NQ ≈ 41.28× QQQ, RTY ≈ 10.09× IWM) and are approximate.

### SPY (last 756.42)
- PDH **762.49** (ES ~7672), PDL **754.93** (ES ~7596), PDC 759.76 (ES ~7644).
- PMH **757.57** (04:38; ES ~7622), PML **755.70** (04:01; ES ~7603). Spot is inside the PM range (no-trade zone) and above the PDL.
- Untested 15-min rejections: **760.9** (Nov 11 14:45), **762.5** (Nov 11 13:45), 768.7–769.2 (Nov 4).
- 2-min EMAs: 13 756.52 < 48 756.64 < 200 757.16, **bearish but bunched** (chop risk).
- **Confluence:**
  - **757–757.6** = PMH + 757 put node (ES ~7616–7622). First lid.
  - **754–755** = PDL 754.93 + 754/755 sign change (ES ~7586–7596). Key shelf; open below it and it becomes resistance.
  - **759.8–761** = PDC + 759–761 sign band + 760.9 untested rejection (ES ~7644–7656).
  - **762.5** = PDH + 762 sign change + untested rejection, with the 763 call node (ES ~7672–7677).
  - **750** put node (ES ~7546) is the downside magnet below the PDL.
- **Game plan:** Break and hold 757.6 on a 15-min close and calls toward 760–761, then 762.5 (PDH); lose 754.9 (PDL) and puts toward 753, then 750 (put node).

### QQQ (last 683.32)
- PDH **695.53** (NQ ~28711), PDL **683.64** (NQ ~28220), PDC 690.30 (NQ ~28495).
- PMH **686.27** (04:38; NQ ~28329), PML **682.04** (04:00; NQ ~28154). **Trading below the PDL**, so 683.64 is resistance unless reclaimed on a 15-min close.
- Untested zones: rejections 692.9 (Nov 11 14:45), 695.6 (Nov 11 13:45); supports **671.0–671.4** and **667.1–668.6** (Nov 10).
- 2-min EMAs: 13 683.79 < 48 684.34 < 200 685.55, **bearish stack**.
- **Confluence:**
  - **683.6–684.0** = PDL + dark-pool cluster 683.8–684.0 (NQ ~28220–28235). Pivot.
  - **685–686.3** = 685 put node + 686.0 dark pool + PMH (NQ ~28276–28329). Overhead lid.
  - **680** = largest put node (NQ ~28070), just under the 682.04 PML. Downside magnet.
  - **690–690.3** = 690 put node + PDC (NQ ~28483–28495).
- **Game plan:** Reclaim 683.6 and break 686.3 (PMH) and calls toward 690 (put node / PDC); lose 682.0 (PML) and puts toward 680 (largest put node), then 675.

### IWM (last 282.64)
- PDH **283.71** (RTY ~2862), PDL **281.48** (RTY ~2839), PDC 282.99 (RTY ~2855).
- PMH **283.18** (04:01; RTY ~2857), PML **282.31** (04:01; RTY ~2848). Inside the PM range.
- Untested zones: rejections **283.62/283.72** (Nov 11), **283.79** (Nov 9), 284.7 (Nov 5); supports **279.6–280.0** (Nov 10), 279.1, 278.4.
- 2-min EMAs: 282.72 / 282.81 / 282.83, **bunched (chop)**, slight bearish tilt.
- **Confluence:**
  - **283.6–284** = PDH + three untested rejections + 284/285 sign change (RTY ~2862–2865). Strong lid.
  - **279–280** = 279 put node + Nov 10 untested supports (RTY ~2814–2824).
- **Game plan:** Break 283.8 and calls toward 285–287 (call nodes); lose 281.5 (PDL) and puts toward 280–279 (put node / untested supports).

**Team2 framing:** re-mark PMH/PML at 9:29; the PM range is a no-trade zone; nothing before 9:45; wait for a 15-min body close beyond a level, then break-and-retest or rejection. QQQ opening below its PDL makes 683.64 resistance.

**History check:** SPY/QQQ flipping from long to short gamma on a single-stock headline gap resembles the negative-gamma starts that came before most big moves in gex_before_moves.md (both directions). Readings are nowhere near the deep −15B to −29B that preceded the sharpest snap-backs, so this isn't that setup.

## Macro and news
**Calendar (ET):**
- **8:30 initial jobless claims**: consensus 194k, prior 189k (Investing.com).
- Fed's Barr and Hammack speak today; **30-yr bond auction 1:00 PM**; Williams in the evening (from last night's calendar pull; times for the speakers not re-verified).
- Fri: 8:30 PPI. NVDA earnings Nov 17; Anthropic IPO planned next week (Yahoo); monthly OPEX Nov 20; FOMC Dec 9.

**Earnings:**
- **Nebius (NBIS)** before the open: revenue **$980.8M vs $907.5M** est. (+571% y/y), loss of $0.13/share, but shares fell after the report (CNBC); call at 8:00.
- After the close today: **CSCO, AMAT, Cerebras**. Last night's after-close reports (FNV, CTVA, etc.) were not index-moving.

**Overnight headlines (Financial Juice / X):**
- **Nvidia:** board crisis meeting (WSJ/NBC); China's grey-market traders hoarding restricted Nvidia chips, Chinese AI firms fear remote-use curbs (00:27); Sen. Cotton urges banning China's CXMT (05:19); Siemens CEO says the NVDA partnership continues as normal (01:56).
- **Iran/oil:** IRGC Navy says two tankers hit explosions on an "unauthorized route" in Hormuz Wednesday night (01:59); Oman says a tanker ran aground off Al Qibliyah (06:38).
- **Russia/Ukraine:** Putin started meeting Witkoff and Kushner (07:07) and warned foreign troops in Ukraine would be targeted (07:34); Russia struck a Naftogaz facility (07:23); Kushner says the US has begun talks with Europe on security architecture.
- **US–China:** Mofcom says China and the US are in close communication on tariff reduction (02:10).
- **UK data beat:** Q3 GDP 0.7% q/q as expected; Sept GDP +0.2% m/m vs 0.0%; manufacturing +0.7% vs −0.5%.
- **BoJ's Asada:** not opposed to hikes, but cautious on speed. ECB poll: all 71 economists see a December hike to 2.75%.
- **Team2Trading (X, last night):** no levels posted; mostly recap of the week (claims 100% alert win rate on the week) and a reply showing Wednesday's 15-min close above the PDH.

**Futures (Yahoo, 7:35 ET vs Wed settle):**
- **NQ 28207 (−0.94%)**, ON high 28368.75 (21:20), ON low 28131.75 (18:15).
- **ES 7610.5 (−0.39%)**, ON high 7628.5, ON low 7600.5.
- **RTY 2851.1 (−0.09%)**, ON high 2859.0, ON low 2844.0.
- Gap: QQQ gaps below its PDL; SPY and IWM open inside Wednesday's range.

**Global:**
- **Asia:** Nikkei −0.70%, Hang Seng −1.26%, Shanghai −0.67%, KOSPI −0.61%; Taiwan fell over 2% (FJ).
- **Europe (~7:30):** STOXX50 +0.15%, **DAX +0.62% (topped 27,000 for the first time; Siemens +4% on record profit)**, FTSE +0.26%, CAC +0.58%. ASML −1.9% earlier (Euronews).

**Cross-asset:**
- **VIX 18.34 (+4.9%)**, overnight 18.13–18.47.
- **10-yr:** cash Treasuries reopen today; last print ~5.00%.
- **DXY 102.94** (flat).
- **Oil:** WTI **85.87 (−0.8%)**, Brent **92.19 (−0.6%)**.
- **Gold 3943 (−1.4%)**, well below $4,000.

## Takeaway (information, not advice)
The Nvidia board headline flipped dealers back to **short gamma** in SPY (−0.95B ex-0DTE) and especially QQQ (−1.95B), so today favors directional moves and whipsaws over yesterday's pin, with an unresolved NVDA decision as live headline risk. The confluence levels that matter most:
- **SPY 754–755** (PDL + sign change; ES ~7586–7596) is the shelf; **757–757.6** (PMH + put node; ES ~7616–7622) is the first lid; **750** (ES ~7546) is the downside magnet.
- **QQQ 683.6–684** (PDL + dark pool; NQ ~28220–28235) is the pivot it's trading under; **680** (largest put node; NQ ~28070) is the magnet below; **685–686.3** (NQ ~28276–28329) caps a reclaim.
- **IWM 283.6–284** (PDH + three untested rejections + sign change; RTY ~2862–2865) is the strongest lid on the board.

Small caps and the Dow are holding up while Nasdaq lags. Wait for claims at 8:30 and the 9:45+ 15-min closes: QQQ reclaiming 683.6 would undercut the gap-down, while losing the PMLs opens the put-node magnets.
