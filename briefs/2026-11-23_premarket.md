# Pre-Market Brief, Mon Nov 23, 2026 (data as of ~7:44 AM ET)

**Relief gap up after the worst week since 2020.** Chips and AI stocks are leading the rebound (NVDA +6.9% to 134.14, SMH +5.1%, MU +4.3%, AVGO +4.6%, GOOGL +5.0%; Yahoo 7:40). The catalyst is Trump's post that he hopes NVDA's board rehires Jensen Huang (CNBC/Yahoo). In deal news, **CrowdStrike is buying Zscaler for $43.9B in stock**: ZS is up 13–15% and CRWD down 7–8% (Investing.com/CNBC).
- **Futures (Yahoo, 7:30, ~10–15 min delayed):**
  - **NQ 25906 (+3.10%)**, overnight range 25462 (Sun 18:10) to **26102.25 (4:15)**
  - **ES 7102 (+2.41%)**, overnight range 6992 to **7142.5 (4:15)**
  - **RTY 2643.6 (+2.17%)**, overnight range 2608.2 to 2652.5
  - All three peaked at 4:15 and have faded since.
- **VIX 31.05 (−13.5%)**, still the highest since the 2025 tariff shock (Yahoo).
- **SPY, QQQ and IWM are all set to open INSIDE Friday's range, well above Friday's close.** Friday's close is now the gap-fill level below. Friday's high is the upside target/resistance.
- **The gamma picture reset after Friday's OPEX:**
  - SPY **−2.16B** (down from −7.49B Friday morning), still short gamma
  - **QQQ +0.07B, about flat, at the gamma pivot**
  - IWM −0.33B, small
- **Not a Friday and not OPEX, but it's a holiday-shortened week:** Thanksgiving is Thursday. The big data comes Wednesday at 8:30 (core PCE, GDP revision).

**Sources:**
- Quant Data API on your account: GEX by strike, dark pool, and 9k+ unconsolidated flow for Fri plus pre-market, pulled 7:44 ET
- Yahoo Finance: 1m/2m/15m bars, futures, global markets, cross-asset
- Financial Juice RSS
- X News
- CNBC, Investing.com, Yahoo live
- TipRanks/WiseView and XTB for the calendar; Tickzen and XTB for earnings
- My 11/20 close recap for Friday's PDH/PDL/close (from Quant Data)

**Caveats:**
- Positioning comes from the Quant Data API, not the browser's My Pages. The 'contract flow' Session Date was not touched (still May 29, 2026), and no filters were added.
- There's no heatmap or interval-map read, so the "magnets" below are the largest GEX nodes.
- No cumulative gamma flip shows near spot. The sign changes listed are per-strike pivots.
- Futures translations are approximate: ES ≈ SPY×10.06, NQ ≈ QQQ×41.30, RTY ≈ IWM×10.07.

---

## Positioning (Quant Data, 7:44 AM ET)

**SPY** (spot 705.99)
- **Net GEX −2.16B** (all) / −2.57B (ex-0DTE). Moderately short gamma, so moves can still extend, but far less than Friday's −7.5B before OPEX.
- **Put nodes:** 680 (−0.73B), 675 (−0.69B), 690 (−0.58B), **700 (−0.57B; −0.67B ex-0DTE)**.
- **Call nodes:** 705 (+0.19B, mostly 0DTE), **715 (+0.17B)**, 720/730 (+0.12B), 800 (+0.24B).
- **Per-strike pivots:** a dense cluster at 702–711, right around spot.
- **Dark pool (pre-market):** 709.1–709.9 (largest) and 706.7–707.0.

**QQQ** (spot 627.20)
- **Net GEX +0.07B** (all) / −0.09B (ex-0DTE). **Essentially at the flip.** The per-strike sign changes cluster at 625–630, so spot sits right on the pivot zone. Above it dealers dampen moves; below it they extend them.
- **Put nodes:** **600 (−0.39B)**, 610 (−0.24B), 620 (−0.22B).
- **Call walls:** 680 (+0.28B), 700 (+0.28B), 660 (+0.19B). These are far above.
- **Dark pool:** 626.9–627.1, at spot.

**IWM** (spot 262.39)
- **Net GEX −0.33B**, small. OPEX cleared most of Friday's −2.0B.
- **Put nodes:** 255 (−0.09B), 254 (−0.08B), 250, 260 (−0.05B), 263 (−0.04B).
- **Call nodes:** 265 (+0.03B), 267 (+0.02B).
- **Pivots:** 262.5–264.
- **Dark pool:** 262.45–262.55.

### 9,000+ contract flow
**Pre-market today (to 7:44): none.**

**Friday Nov 20 (299 prints, all tickers; index highlights below, times ET):**
- **Early protection buying at the ask (continuation, and it worked):**
  - SPY 650P 2/19, 15,000 @ $13.56 ask, $20.3M, opening, 10:32
  - SPY 655P 1/29, 3 × 10,000 @ ~$12.3–12.6 (ask/below bid), ~$37M, opening, 10:51–11:16
  - QQQ 460P 5/21, 10,000 @ $9.25 ask, opening, 13:08
- **Hedge roll-downs and monetization (the afternoon and the close):**
  - **SPY 3/19 put spread rolled down at 13:47.** Closed the 690P/590P (26,000 each, below bid, ~$102M). Opened the 660P/560P (28,000 each, below bid, ~$79M).
  - **SPY 13:52:** closed 605P 3/19 (60,000 @ ask, $69M) and opened 600P 4/16 (50,000 @ bid).
  - **SPY 11/27 at 16:00:** closed **700P (44,500, ITM, $91M)** and 675P. Opened 680P and 660P (66,750 each, above ask, ~$125M).
  - **SPY 12/4 at 16:03:** closed **700P (44,500, ITM, $97M)**. Opened **675P (133,500 @ $13.07 above ask, $174.5M)** and sold 650P (89,000 @ bid, $67M), which looks like a put spread/ratio.
  - **Read:** big holders cashed in in-the-money 700 puts and re-struck lower. That pulled hedge support away from 700 and moved it down to 675–680, which matches today's SPY put nodes at 675/680.
  - **SPX:** two large same-timestamp roll-outs (11:46 and 13:05, ~41–43k lots per leg). Closed the Nov/Dec 6250–6500 puts and opened Dec 31 / Jan 8 5800–6000 put spreads. That's protection pushed further out and lower.
  - **IWM 13:47:** closed ITM 265P 12/4 (34,462 below bid, $29M) and opened **254P 12/4, 56,092 at the bid, $21.4M**. That's put selling at the bid during negative GEX.
- **Upside bets:**
  - **QQQ 12:45:** opened 635C 3/19 (10,000 @ $38.42 ask, **$38.4M**) and closed 655C 12/18 at the bid. A call roll down/out: a big bet on a rebound toward 635+.
  - META and AMZN call roll-downs (13:00 area).
- **Bearish VIX:** VIX calls were closed all day (Dec 20C/24C/28C, Jan 35C/45C; 10k–56k lots), which is profit-taking. VIX Jan 23P (20,000 @ ask) and 19.5P (40,000) were **opened** at 11:27, a bet that vol fades by January.
- **Call selling:** NVDA 240C 1/19, 10,343 @ $14.10 bid, opening, $14.6M, 10:54.
- **Lottery/structure prints:** AAPL 140–150P 11/27 @ $0.01 and SPY 605P 11/23 @ $0.12–0.13 (55k total). Small premium, not directional.

**Read:** Friday morning's put buying at the ask was **continuation**, and it worked: SPY ran from 718 to 687. The afternoon flipped to **hedge monetization**: ITM 700 puts closed, puts rolled lower, IWM puts sold at the bid, VIX calls cashed and VIX puts bought. In my history file, heavy put selling and monetization at the bid in deep negative GEX came before the cleanest **snap-back rallies** (Jun 10→11, Jul 28→30). Today's gap up fits that pattern. That study also shows short gamma lets moves run both ways, and today's gap is already fading from the 4:15 highs.

---

## Combined levels map (Team2Trading layer + GEX)

- **PDH/PDL/close:** Friday RTH (Quant Data).
- **Pre-market:** 4:00 AM to ~7:44 AM ET (Yahoo 1m). **Still live, can change before 9:30.**
- **Zones:** 15-min swing highs/lows from Nov 19–20.

### SPY (pre-market ~706.0)
| Level | Price | Type | ES ≈ |
|---|---|---|---|
| **PDH** | **718.27** | target/resistance; **+ 715.5–718.6 Thu 15m lows + 715 call node** | **7226** |
| 15m zone | 711.72 (Fri 9:30 low, untested) | resistance | 7160 |
| **PMH** | **711.01 (4:17)** | **+ 711 pivot, 709.9 dark pool, ES ONH 7142.5** | 7153 |
| PML | 704.06 (4:04) | **+ 703.98 Fri 13:45 15m high** | 7083 |
| GEX | **700 put node** / 699.01 Fri 15m low | support/magnet | 7042 / 7032 |
| Fri close / gap fill | 690.56 | **+ 690 put node** | 6947 |
| PDL | 686.81 | | 6909 |
- **2-min EMA stack:**
  - 13 = 706.80, 48 = 708.16, 200 = 705.19.
  - 13 is under 48 and price is between them, just above the 200, so it's **bunched/chop**. The short-term tilt is down because the gap is fading.
- **Confluence levels:**
  - **709.9–711.7:** PMH + Fri 15m low + pivot + dark pool + ES ONH.
  - **703.98–704.06:** PML + Fri 15m high.
  - **699–700:** put node + Fri 15m low.
  - **690–690.6:** gap fill + put node.
  - **715.5–718.3:** PDH + 715 call node + Thu zone.
- **Game plan:** A 15-min close above 711.7 after 9:45 puts calls toward 715–718.3 (call node/PDH). Lose 704 on a 15-min close and puts toward 700, then 690.6 (gap fill + put node). Between 704 and 711, it's the pre-market box: no trade.

### QQQ (pre-market ~627.1)
| Level | Price | Type | NQ ≈ |
|---|---|---|---|
| **PDH** | **643.17** | target/resistance; + 644.3 Thu 15m low | **26563** |
| 15m zone | 633.86 (Fri 9:30 low) | **+ PMH 633.49** | 26178 |
| **PMH** | **633.49 (4:17)** | ≈ NQ ONH 26102 area | 26163 |
| GEX pivot | 625–630 (flip zone) / dark pool 627 | | 25822–26019 |
| PML | 626.44 (4:01) | **+ 625.22 Fri 13:45 15m high** | 25872 |
| GEX | **620 put node** / 618.72 Fri 15m low | | 25606 / 25553 |
| Fri close / gap fill | 610.10 | **+ 610 put node** | 25197 |
| PDL | 606.30 | then 600 put node (largest) | 25040 |
- **2-min EMA stack:** 628.15 / 629.48 / 626.43. Same as SPY: **bunched/chop**, short-term tilt down.
- **Confluence levels:**
  - **633.5–633.9:** PMH + Fri 15m low.
  - **625.2–626.4:** PML + 15m high + gamma-flip zone. This is the key level: **below it QQQ moves into negative gamma** and moves extend.
  - **618.7–620:** put node + 15m low.
  - **610:** gap fill + put node.
- **Game plan:** A 15-min close above 633.9 puts calls toward 643.2 (PDH). Lose 625.2 and puts toward 620, then 610 (gap fill). QQQ is sitting near the bottom of its pre-market box (626.4–633.5), so wait.

### IWM (pre-market ~262.4)
| Level | Price | Type | RTY ≈ |
|---|---|---|---|
| **PDH** | **265.77** | **+ 265.3 Thu zone + 265 call node** | **2676** |
| 15m zone | 264.0–264.24 (Thu lows) | resistance; 264 pivot | 2658 |
| **PMH** | **263.45 (6:46)** | + 263 node | 2653 |
| 15m zone | 262.62 (Fri 9:30 low) | inside the PM box | 2645 |
| PML | 261.41 (4:01) | + 260.93 Fri 15m high | 2632 |
| GEX | 260 put node | | 2618 |
| 15m zones | 258.7–259.0, 257.5 | | 2605 / 2593 |
| Fri close / gap fill | 256.91 | then PDL 256.13, 255/254 put nodes | 2587 / 2579 |
- **2-min EMA stack:** 262.54 / 262.68 / 261.42, bunched/chop.
- **Confluence levels:**
  - **265.3–265.8:** PDH + zone + call node.
  - **260.9–261.4:** PML + 15m high.
  - **256.1–256.9:** gap fill + PDL, near the 255 node.
- **Game plan:** A 15-min close above 264.2 puts calls toward 265.3–265.8 (PDH/call node). Lose 260.9 and puts toward 260, then 258.7. The pre-market box is tight (261.4–263.5) and a no-trade zone.

### Bias framing (Team2Trading)
- All three open **inside Friday's range**, above the close and below the PDH, so there's no break-and-retest of a PDH/PDL at the open.
- The trade is a 15-min close beyond the pre-market box. Above the PMH, the PDH is the target. Below the PML, the gap fill is the target.
- A rejection at the PMH/15m zone keeps the fade-the-gap scenario in play.
- Nothing before 9:45 ET. **The US flash PMIs print at 9:45**, so the first clean 15-min bar is the 10:00 close.

### History parallels
- The setup is **a flush in deep negative gamma followed by a catalyst gap up** (Fri SPY −3.5% with VIX up to 40, then the Huang headline). It resembles **Jun 10→11 and Jul 29→30** in my GEX file: snap-back rallies after the deepest short-gamma readings.
- Friday's late hedge monetization lines up with the "put selling at the bid" signal.
- The caveat: in those cases the snap-back held after the open. Today the futures have already faded ~0.7% from their 4:15 highs (NQ 26102 → 25906), so the PMH/PML break decides it.

---

## Macro

**Calendar (ET):**
- **8:30** Chicago Fed National Activity Index (Oct): consensus 0.4, prior 0.07 (minor).
- **9:45** **S&P Global flash PMIs (Nov):**
  - Manufacturing: consensus 54.5, prior 54.9
  - Services: consensus 55.6, prior 56.1
  - Composite: prior 55.9
- **4:00 PM** NY Fed **Williams** speaks.
- **Rest of the week:** Tue consumer confidence and DELL after the close. **Wed 8:30 core PCE (Oct), Q3 GDP revision, new home sales.** Thu Thanksgiving, markets closed. Fri early close.
- **Europe flash PMIs this morning were mixed:**
  - Germany beat strongly (composite 55 vs 53.2).
  - France missed (composite 46.2 vs 47.9).
  - Eurozone composite 51.7 vs 52.
  - UK composite 52.3 vs 52.8.

**Earnings:**
- **Before the open:** ANF, BURL, DKS, KSS, DRVN, GDRX, DAVA, VNET. Retail only, no index movers (no S&P 500 reports before the open per WiseView).
- **After the close today:** **HPE** (AI servers), A, ZM, TCOM, SYM.
- **After the close Fri:** nothing index-moving.

**Financial Juice (ET):**
- **Sun 18:35:** Houthis attack Saudi Arabia's Rabigh refinery.
- **Sun 18:51:** Libya's NOC says a valve closure on the Sharara pipeline cuts ~350k bpd.
- **Sun 20:06:** California AG sues OpenAI over model security.
- **2:49:** Iran's foreign ministry says it will use "all available tools" against the US naval blockade.
- **4:22:** TSMC's Hou says the AI trend is unchanged and clients aren't adjusting orders.
- **4:55:** Sen. Schiff plans a no-AI-bailouts resolution.
- **7:14:** Allies warn Russia may launch a nuclear space weapon next month.
- **7:43:** Deutsche Bank sees the S&P 500 at 9,000 in 2027.

**X News:**
- Futures are rebounding after the S&P/Dow closed in correction and the Nasdaq-100 briefly hit bear-market territory Friday.
- Trump blames Democrats' midterm wins for the selloff.
- Citi calls the AI bubble "burst" after NVDA −13%. NVDA is down ~48% from its October peak on Huang's exit and an SEC probe.
- Nasdaq and NYSE Arca plan 23/5 trading starting Dec 6.
- India's Nifty fell 1.7%.

**Global:**
- **Asia:** Japan closed for a holiday. **KOSPI −3.31%** (SK Hynix led the losses). Hang Seng −0.12%, Shanghai +0.15%.
- **Europe (7:25):** Stoxx 50 +0.80%, DAX +0.76%, CAC +0.67%, FTSE +0.57%.

**Cross-asset:**
- **10-year 4.959% (+4 bp)**, 2-year 4.689% (+7 bp) (CNBC 5:15). Yields are rising with the risk-on move.
- **DXY 103.90 (+0.1%)**.
- **WTI $82.12 (−2.2%)** and **Brent $88.51 (−4.4%)**, falling despite the Libya and Houthi supply headlines.
- **Gold $3,617 (+2.9%)**.
- **VIX 31.05 (−13.5%)**.

---

## Takeaway (information, not advice)
- **Pre-market boxes (no-trade zones):**
  - SPY 704–711
  - QQQ 626.4–633.5
  - IWM 261.4–263.5
- **The strongest confluences:**
  - **Upside:** SPY 709.9–711.7 (≈ ES 7142–7160, the overnight high) and QQQ 633.5–633.9 (≈ NQ 26163–26178).
  - **Downside:** SPY 704 and 700 (put node), QQQ 625.2–626.4 (gamma-flip zone).
- **Gap-fill magnets:** SPY 690.6 / QQQ 610 / IWM 256.9, each with a put node.
- **Upside magnets:** the PDHs SPY 718.3 / QQQ 643.2 / IWM 265.8, with SPY's 715 and IWM's 265 call nodes.
- **QQQ is the swing factor:** holding above ~626 keeps dealers near neutral. Losing it puts QQQ back in short gamma.
- **The 9:45 PMIs** land exactly at Team2Trading's first entry window.

