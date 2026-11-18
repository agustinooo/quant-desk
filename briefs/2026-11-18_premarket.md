# Pre-Market Brief, Wed Nov 18, 2026 (data as of ~7:47 AM ET)

**NVDA's beat is being sold into, and Waller just turned very hawkish.** NVDA is **+2.8% (159.84)**. The board said it won't bring back Huang. From 7:36 to 7:46 ET, **Fed's Waller (CNBC) said "if you are not going to signal a more aggressive pace... the Fed needs to do 50 bps now"** and that the Fed "may have to do more than reverse the cuts it made last year." SPY and IWM printed their pre-market lows at 7:43. Futures at 7:38 ET (Yahoo, ~10 min delayed): **NQ 27247 (+0.6%)**, **ES 7375.75 (+0.2%)**, **RTY 2705.7 (−0.2%)**. All are well off their overnight highs (NQ 27609.75, ES 7434.75, set at 18:05–18:10 on the NVDA pop). **VIX 24.25 (−4.4%).** **Oil is down 2–3% (WTI 84.17).** **Gold is down 2.7% (3758).**

**Positioning:**
- SPY: mildly short gamma (**−0.83B**).
- QQQ: **long gamma (+0.75B, up from +0.26B)**.
- IWM: close to flat (**−0.16B**).

**Today's calendar:** 8:30 housing starts/permits, **2:00 PM FOMC minutes**, Fed speakers Barr 1:35, Williams 2:30, Kashkari 4:15, and PANW after the close. **It's Wednesday and not monthly OPEX.** Monthly OPEX is Fri Nov 20. VIX Nov options expire today, going by the Nov 18 VIX expiries in the flow.

**Sources:** Quant Data API on the user's account (GEX by strike, dark pool, 9k+ unconsolidated flow; pulled 7:47 ET), Yahoo Finance (1m/2m/15m bars, futures, global, cross-asset), Financial Juice RSS, X News, MarketScreener/WSJ survey and Investing.com (calendar), Nexqual (earnings), and my 11/17 close and after-hours recaps.

**Caveats:**
- Positioning came from the Quant Data API, not the browser My Pages. The 'contract flow' Session Date (May 29, 2026) wasn't touched and no filters were added. The browser sign-in wasn't checked, but the API key worked.
- Yahoo futures quotes run about 10 minutes behind, so the 7:38 quotes are from before most of Waller's remarks.
- No gamma flip shows near spot (cumulative): QQQ's only cumulative flip is way up at 700. The "sign changes" listed are per-strike.
- There's no live 10-year quote. **5.10% is Tuesday's close.**

## Positioning (Quant Data, 7:47 AM)
- **SPY** (spot 733.3): net GEX **−0.83B** all / −0.97B ex-0DTE. That's about the same as yesterday (−0.97B) and nothing like the −15B to −29B readings in the history file.
  - Puts: **722 (−0.35B)**, 700 (−0.31B), **736 (−0.30B, just above spot)**, 724 (−0.29B), 726 (−0.26B).
  - Calls: **750 (+0.38B)**, 800 (+0.27B), **745 (+0.25B)**, **740 (+0.23B)**, 755 (+0.22B).
  - Sign changes cluster at **733–737**, which is a pivot band right at spot.
  - Dark pool today: 735.8–737.0, with 734.0–734.5 in range.
- **QQQ** (spot 660.45): net GEX **+0.75B** all / +0.56B ex-0DTE. That's long gamma, and it's grown since yesterday, so expect more dampening and pinning.
  - Puts: **650 (−0.50B, the largest)**, 640 (−0.41B), 645 (−0.22B), 655 (−0.19B).
  - Calls: **700 (+0.60B)**, 680 (+0.38B), **670 (+0.33B)**.
  - Sign changes: **660 / 662**, 654–656, and 675/676.
  - Dark pool: 663.7–664.75 (top prints), with 660.25–662.1 in range.
- **IWM** (spot 267.95): net GEX **−0.16B**, roughly flat.
  - Puts: **260 (−0.18B)**, 258, 265, plus small 267/268 nodes.
  - Calls: **272 (+0.07B)**, **273 (+0.06B)**, 271.
  - Sign change: 270. Dark pool: 269.4–269.6 above and 268.0 at spot.

### 9,000+ contract flow
**Pre-market today:** no 9k+ prints so far. The API's pre-market page returned 0 rows, and a lack of prints doesn't mean calm.

**Prior session (Tue Nov 17; 144 prints; structure read from the close pull):**
- **SPY, 11:02–11:03, right after the 727 low, all opening above the ask:**
  - Nov 27 725P/710P, **55,625 each**.
  - Nov 27 700P/675P, 44.5k each, plus **Dec 4 700P/675P, 44.5k each**.
  - Same-timestamp legs, so likely a put-spread roll plus protection bought back into the flush. About $125M in puts at the ask.
- **SMH, 10:50:** Sep '27 380P, **20k sold at the bid, opening (~$67M)**. That's long-dated put selling at the low.
- **QQQ:**
  - 9:37: Nov 30 675C, **12k at the ask, opening ($10.7M)**.
  - 10:03 and 10:26: Nov 20 640P, **9k at the ask** each. Tied multi-leg, so likely spread legs.
  - 13:03: Dec 660P, **10k sold at the bid, closing (~$25M)**. A hedge monetized.
- **IWM:**
  - 10:06: Nov 27 270P bought / 275P sold, **30,065 each**, opening. A same-timestamp spread.
  - 12:11: Dec 4 275P rolled down to 265P (37.4k).
  - 15:45: Dec 250P, 25k, closing.
- **VIX:**
  - Dec 1 24C/28C call spread, 45.5k, opening.
  - Upside rolled out to January (45C/65C).
  - Dec 50C → Jan 70C (84k).
- **NVDA:** Jan 140P, 10k sold at the bid, closing.

**Read:** The flow looks like hedges being monetized and rolled at the lows (SMH/QQQ selling at the bid), while protection was re-bought and VIX upside was extended. That's mixed, not a clean sweep-reversal signal.
- In the history file, the cleanest snap-backs came after heavy put selling at the bid **during deep negative GEX** (−15B to −23B). Today's SPY −0.83B is shallow, so the analog is weak.
- Futures did bounce overnight on NVDA (NQ to 27609.75), but they've given most of it back.
- **Lean: no big-print evidence of a trend continuation either way. Treat it as headline/Fed-driven.** Information, not advice.

## Combined levels map (Team2Trading + GEX)
PDH/PDL are Tuesday's RTH. PMH/PML cover 4:00 to 7:47 ET (Yahoo 1m) and **can still change before 9:30**, especially after 8:30 housing data and more Waller headlines.

The 2-min 13/48/200 EMA stack is **bearish on all three**:
- SPY: 733.87 / 734.78 / 735.41
- QQQ: 661.02 / 662.16 / 662.52
- IWM: 268.44 / 268.90 / 269.45

In each case price is below the 13.

Futures equivalents use 7:38 ratios (ES ≈ 10.058× SPY, NQ ≈ 41.26× QQQ, RTY ≈ 10.10× IWM) and are **approximate**.

### SPY (last 733.3, ES ≈ 7375)
| Level | SPY | ES ≈ | Notes |
|---|---|---|---|
| Call wall | 750 | 7544 | largest call node |
| Call node | 745 | 7493.5 | |
| **PDH / call node** | **739.76 / 740** | **7441–7443** | **CONFLUENCE.** PDH + 740 call node (0.03%). 15-min R from 11/17 09:45 |
| **PMH / put node / DP** | **737.39 / 736–737** | **7403–7417** | **CONFLUENCE.** PMH (4:42) + 736 put node (−0.30B) + DP 736.97 + sign-change band |
| PM low | 732.54 (7:43) | 7368 | live, set on Waller |
| **PDL / put node** | **727.00 / 726** | **7302–7312.5** | **CONFLUENCE.** PDL + 726 put node (0.14%) |
| Put nodes | 724 / 722 | 7282 / 7262 | 722 is the biggest put node |

- **Bias framing:** Spot is inside the PM range (732.54–737.39), which is a no-trade zone. Above PDL, and 7 points under PDH.
- **Game plan:** 15-min close above 737.4 (PMH/736 put node) and calls toward 739.76–740 (PDH/call node), then 745. Lose 732.5 (PML) on a 15-min close and puts toward 727/726 (PDL/put node), then 722.

### QQQ (last 660.45, NQ ≈ 27247)
| Level | QQQ | NQ ≈ | Notes |
|---|---|---|---|
| Call wall | 680 | 28054 | |
| **Call wall / 15-min R** | **670 / 669.85** | **27635–27641** | **CONFLUENCE.** 670 call (+0.33B) + untested R from 11/16 11:30 (0.02%). 672.14 R above |
| PM high | 665.18 (5:07) | 27442.5 | |
| **PDH / DP** | **663.36 / 663.7** | **27367–27381** | **CONFLUENCE.** PDH + top dark-pool prints (0.05%) |
| Pivot | 662 / 660 | 27311 / 27226 | per-strike sign changes; 2-min 200 EMA 662.52 |
| PM low | 658.61 (4:01) | 27171 | |
| Put node | 655 | 27022.5 | |
| **Put wall / 15-min S** | **650 / 649.89 / 651.0** | **26816–26858** | **CONFLUENCE.** Largest put node (−0.50B) + two untested S zones |
| **PDL** | **646.65** | **26678** | 15-min S (11/17 10:45); 645 put node 0.26% below |

- **Bias framing:** Inside the PM range (658.61–665.18), which is a no-trade zone. Long gamma favors chop and pinning around 660–662 unless the Fed headlines push it out.
- **Game plan:** 15-min close above 665.2 (PMH) and calls toward 669.85–670 (call wall/R); a reclaim of 663.4 (PDH) is the first tell. Lose 658.6 (PML) and puts toward 655, then 650/651 (put magnet).

### IWM (last 267.95, RTY ≈ 2706)
| Level | IWM | RTY ≈ | Notes |
|---|---|---|---|
| **PDH / call nodes / 15-min R** | **273.05 / 273 / 273.27–273.37** | **2757–2760** | **CONFLUENCE.** PDH + 273 call node + two untested R zones |
| Call node | 272 / 271 | 2746.5 / 2736.5 | |
| PM high | 269.76 (4:31) | 2724 | DP 269.4–269.6 just below |
| **PML / PDL / S zone** | **267.95 / 267.86** | **~2705** | **CONFLUENCE.** PM low (7:43) sits on PDL and the 11/17 10:45 S zone (0.03%). Small 267/268 put nodes |
| Put nodes | 265 / 260 | 2676 / 2625.5 | 260 is the largest |

- **Bias framing:** IWM is **sitting on PDL right now**. If it opens below 267.86, PDL becomes resistance (his rule).
- **Game plan:** 15-min close below 267.86 and puts toward 265, then 260 (put wall). Reclaim and hold above 269.76 (PMH) and calls toward 271–272.

## Futures / Globex (Yahoo, 7:38 ET; vs Tuesday settle)
- **NQ 27247.25 (+0.6%).** ON range 27093 (21:45) to **27609.75 (18:05)**.
- **ES 7375.75 (+0.2%).** ON range 7363.25 (21:50) to 7434.75 (18:10).
- **RTY 2705.7 (−0.2%).** ON range 2703.7 (07:35, the low, still pressing) to 2727 (18:10).
- **The NVDA pop at the 6 PM reopen faded.** NQ is about 360 points under its overnight high. Tuesday's RTH lows: ES 7308, NQ 26658.5, RTY 2699.5.

## Mega-caps / chips (pre-market, 7:45)
- **Chips are up:** NVDA +2.8% (159.84), CRWV +3.6%, AVGO +1.8%, AMD +1.5%, RGTI +2.1%.
- **The rest:** GOOGL +0.8%, TSLA +0.5%, AMZN +0.4%, CSCO +0.4%, MSFT −0.1%, META −0.2%, AAPL −0.3%.
- **NVDA headlines (X News):**
  - The board unanimously rejected Huang's return.
  - A new national-security and export-control oversight committee.
  - Trump backed Lutnick over Bessent on chip-export enforcement.
  - House Democrats are probing the Lutnick family's NVDA trades.
  - Cramer blames analyst downgrades for the muted rally.

## Macro
**Calendar (ET):**
- **07:36–07:46 Fed's Waller (CNBC, done):**
  - "Very concerned inflation is heading in the wrong direction and broadening."
  - "Needs to do 50 bps now" if the Fed won't signal a faster pace.
  - The Fed may need to "shock" inflation expectations.
  - He also sees nothing "bubble-like" in AI pricing.
- 07:00: MBA mortgage applications −2.3% (prior +6.2%); 30-year rate 7.35% (prior 7.21%).
- **08:30 Housing starts (Oct):** consensus 1.25M, prior 1.221M. **Building permits:** consensus 1.38M, prior 1.40M.
- **10:00 Pending home sales (Oct):** consensus −1.5%, prior −7.3%.
- **13:35 Fed's Barr.** **14:00 FOMC minutes** (Oct 27–28 hold, 10–2 vote). **14:30 Fed's Williams.** **16:15 Fed's Kashkari.**
- Tomorrow: 8:30 jobless claims (consensus 197K) and Philly Fed (consensus 18.0).

**Earnings:**
- **Before the open:**
  - **TGT beat:** adj EPS $2.65 vs $2.07, revenue $27.07B vs $26.45B.
  - **LOW beat:** $3.10 vs $2.86, revenue $22.76B vs $22.34B.
  - TJX (BusinessWire: comp +4%, margin and EPS above plan).
  - Also BRBR (EPS miss), JJSF, ZIM, GLNG, BLSH, GLBE.
- **After the close:** **PANW** ($253B; EPS estimate $0.97), plus Everpure (P), WWD, SNEX, KLIC.
- **Last night:** NVDA beat and raised (Q4 guide $130B ±3%). It's up about 2.8%, well inside its ±8.5% implied move.

**Financial Juice (overnight, ET):**
- **Hormuz:**
  - 04:42: UKMTO late report of a tanker struck by a projectile 13NM north of Khasab.
  - 01:28: Adnoc said a vessel was attacked transiting Hormuz on Nov 17.
  - 04:05: Saudi civil defense warning of a possible threat in Jazan.
  - 02:05: Israel's Katz said Israel is ready to seize more territory if fronts escalate.
- **APEC (Shenzhen):**
  - Xi greeted Trump on arrival.
  - Trump and Putin shook hands, and the Kremlin says they will talk.
  - Trump is also meeting Mexico's president and Canada's PM.
  - Sources say the Trump administration is weighing whether US firms must disclose China AI use.
- **Europe:**
  - UK CPI 3.6% y/y (in line); core 2.8%; PPI input +10.8% y/y (vs 9.2%). The BoE December hike odds slipped to 80% from 90%.
  - Eurozone final CPI 4.0% (core 2.6% vs 2.5%).
  - ECB's Vujcic: "a December hike looks very likely."

**X news:**
- Oil hit multi-week lows on a 5.3M-barrel US crude build.
- US refining margins fell 36% from Oct 9; gasoline is near an eight-month low (~$3.78).
- Citi says about 95% of S&P longs are underwater ($45.9B at risk), and the recent bounce was mostly short covering.

**Global (Yahoo):**
- **Asia:** Nikkei +0.3%, Kospi +2.0%, Hang Seng −0.9%, Shanghai +0.1%.
- **Europe (7:30):** Stoxx 50 flat, DAX −0.1%, CAC −0.2%, FTSE −0.5%.

**Cross-asset:**
- **VIX 24.25 (−4.4%).** ON range 23.47–24.43, and it ticked up into 7:00.
- **WTI 84.17 (−2.1%)**, ON low 82.38 at 3:40. Brent 90.21 (−3.2%).
- **Gold 3758 (−2.7%)**, at its overnight low.
- **DXY 103.86 (+0.3%)**, near its overnight high.
- 10-year: 5.10% (Tuesday's close; no live quote).

## Takeaway (information, not advice)
- **Top confluence levels:**
  - **SPY:** 739.76/740 (PDH + call node) and 736–737.4 (PMH + put node + dark pool + pivot band). 727/726 below (PDL + put node).
  - **QQQ:** 670 (call wall + untested R) and 650/651 (largest put node + two S zones). 663.4 (PDH + dark pool) is the first tell.
  - **IWM:** it's sitting on 267.86–267.95 (PDL = PML = S zone). The **lid is 273.05** (PDH + call node + R).
- **Magnets:** QQQ is long gamma (+0.75B), so 660–662 can pin. SPY's 736 put node sits just above spot.
- **Event risk:**
  - Waller's hawkish turn is landing now.
  - The 8:30 housing data and the 2:00 PM FOMC minutes can reset the ranges.
  - Short-dated put buying into an event has tended to precede whipsaws (history file).
- **His rules:** Don't trade inside the PM range, wait for 15-min closes at 9:45 or later, and an open under PDL turns it into resistance (watch IWM).
