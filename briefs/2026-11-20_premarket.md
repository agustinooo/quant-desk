# Pre-Market Brief, Fri Nov 20, 2026 (data as of ~7:45 AM ET)

**Sixth straight S&P loss is extending: tech/chips gap down again, today is monthly OPEX.** Anthropic is ~6–9% lower pre-market after its debut (closed Thu $97.17 vs $83 IPO; Investing.com/CNBC), and chips are leading lower worldwide (AMD −6.9%, AVGO −3.8%, META −3.6%, NVDA −3.0%, CRWV −6.0%, Yahoo ~7:40). INTU −10–11% on guidance cut + Mailchimp sale.
- **Futures (Yahoo, 7:30, ~10–15 min delayed):** **NQ 26152 (−1.69%)**, **ES 7137.25 (−0.83%)**, **RTY 2657.3 (−0.23%)**.
- **VIX 30.52 (+7.3%)**, first print above 30 since March (X News); VIX futures in backwardation per traders on X.
- **SPY, QQQ, IWM all indicated BELOW yesterday's lows** → yesterday's low is now resistance (Team2Trading rule).
- **Dealers short gamma across the board:** SPY **−7.49B**, QQQ **−3.60B**, IWM **−2.03B**. A large share is 0DTE that expires today (SPY ex-0DTE −2.95B, IWM ex-0DTE only −0.22B), so the gamma picture can change sharply after today's expiry.
- **OPEX Friday:** Team2Trading trades it lightly.

**Sources:** Quant Data API on your account (GEX by strike, dark pool, 9k+ unconsolidated flow for Thu + pre-market; pulled 7:44 ET), Yahoo Finance (1m/2m/15m bars, futures, global, cross-asset), Financial Juice RSS, X News, CNBC / Investing.com / Yahoo Finance live / US News (Reuters), FXStreet (10-yr), Federal Reserve calendar + Econoday (calendar), Clometrix (UMich consensus), TokenPost/The Right Trader (earnings), my 11/19 close recap (PDH/PDL from Quant Data).

**Caveats:** Positioning comes from the Quant Data API, not the browser My Pages (I didn't open the browser; the 'contract flow' Session Date was not touched and stays May 29, 2026; no filters added). No heatmap/interval-map read this morning, so "magnets" below are the largest GEX nodes. No cumulative gamma flip near spot on any of the three (the sign changes listed are per-strike pivots). Yahoo printed a bad SPY tick at 4:00 (692.15 low); I'm ignoring it. Futures translations are approximate (ratios at 7:30: ES ≈ SPY×10.06, NQ ≈ QQQ×41.29, RTY ≈ IWM×10.08).

---

## Positioning (Quant Data, 7:44 AM ET)

**SPY** (spot 709.31)
- **Net GEX −7.49B** (all) / −2.95B (ex-0DTE). Deep short gamma, moves extend. Down from −20.2B at yesterday's close (spot moved and the book re-marked), but still deep.
- **Put walls:** **700 (−2.26B, by far the biggest node; −1.54B ex-0DTE)**, 705 (−0.55B), 690 (−0.52B), 718 (−0.42B), 695 (−0.41B).
- **Call walls (small):** 800 (+0.22B), 750 (+0.13B), 725 (+0.10B), 740 (+0.09B).
- **Per-strike pivots:** 720–726. No cumulative flip.
- **Dark pool (pre-market):** 711.6–713.8 cluster above spot, small size.

**QQQ** (spot 633.33)
- **Net GEX −3.60B** (all) / −1.45B (ex-0DTE). Flipped short yesterday and deeper now.
- **Put walls:** **640 (−0.70B)**, **630 (−0.59B)**, 650 (−0.54B), 625 (−0.47B), 620 (−0.39B).
- **Call walls:** 700 (+0.34B), 680 (+0.18B), 690 (+0.15B).
- **Pivots:** 636–637, 646–647. **Dark pool:** 634–636.

**IWM** (spot 263.64)
- **Net GEX −2.03B** (all) / **−0.22B (ex-0DTE)**: almost all of IWM's short gamma is today's expiry.
- **Put walls:** **265 (−0.54B)**, 263 (−0.30B), 262 (−0.30B), 261 (−0.26B), 259 (−0.19B).
- **Call walls:** tiny (272 +0.03B, 271 +0.02B).
- **Pivots:** 266–268. **Dark pool:** 263.8–264.2.

### 9,000+ contract flow
**Pre-market today (to 7:44):** none.

**Thursday Nov 19 (186 prints; index/mega-cap highlights, times ET):**
- **IWM 270P 11/27, 23,018 @ $2.86 above ask, $6.6M, opening, 9:31** (spot 271.26). Aggressive put buying at the top of the day → **trend-continuation** signal that worked (IWM −2.2%).
- **QQQ 660P 11/30, 9,450 @ $8.10 ask, $7.7M, opening, 10:08** (spot 672.63). Bearish, early, continuation.
- **SPY 712P/704P 11/30, 9,000 each, 9:35**: opened 712P at ask, closed 704P mid → roll **up** of puts (adding protection).
- **SPY 775C 12/31, 29,144 total @ ~$3.18 ask, ~$9.3M, opening, 10:10**. Far-OTM upside lottery; didn't help yesterday.
- **QQQ 655C 12/18, 10,000 @ $20.78 ask, $20.8M, opening + 720C 12/18 30,000 @ $1.78 bid, closing, 14:10** (spot 648). Same-timestamp **call roll down** into closer strikes: a large bet on a rebound toward 655+ by Dec.
- **IWM 252P/255P 12/18, 15,000 each, 12:07** (open 252 at bid / close 255): put roll down. **IWM 252P + 251P 12/18, 12,500 each at bid/mid, opening, 16:06**: put **selling** after the close.
- **XSP 695P 1/29, 10,357 @ $13.79 below bid, $14.3M, opening, 11:52.**
- **VIX:** repeated closes of Dec 17/18/19/20 puts (~20k–38k lots) and big **closing** of VIX 45C/65C (Dec + Jan, 21k–120k lots) at 14:13 → hedge holders cashing in calls as VIX ran to 28.
- **Deep-ITM 11/20 expiry blocks (structure, not direction):** NVDA 200–220P (spot ~148; ~$1B+ notional, 14:27–14:58), SPY 750P/765P 11/20 (40k at bid, 14:35), QQQ 705P/710P 11/20 (~60k, 15:27–15:49), IWM 280P 11/20 (15k, 15:21). Most likely expiry-day closing/rolling or financing trades, so I'm not reading them as directional.

**Read:** the directional prints early Thu (IWM/QQQ puts at the ask) were **continuation**, and they worked. Late-day, the structure shifted toward VIX call profit-taking, QQQ call roll-downs, and some IWM put selling at the bid. In my history file, heavy put selling at the bid in deep negative GEX came before the cleanest snap-backs (Jun 10→11, Jul 28→30). Thursday's put selling was small compared with those, so it's a **weak** snap-back hint at best.

---

## Combined levels map (Team2Trading layer + GEX)

PDH/PDL = Thu RTH (Quant Data). Pre-market = 4:00 AM to ~7:45 AM ET (Yahoo 1m; **still live, can change before 9:30**). Zones = 15-min swing highs/lows from Nov 17–19.

### SPY (pre-market ~709.3)
| Level | Price | Type | ES ≈ |
|---|---|---|---|
| PDH | 739.76 | | 7444 |
| 15m zones | 717.5–718.6 (Thu 12:00–14:00 lows) | resistance; **+ 718 put node** | 7220–7230 |
| **PDL** | **715.51** | **resistance (opening below)**; Thu close 715.87 | **7200** |
| PMH | 714.96 (4:03) | | 7194 |
| PML | ~709.26 (7:44, current low) | | 7137 |
| GEX | 705 put node / **700 put wall (−2.26B)** | magnet | 7094 / 7044 |
- **2-min EMA stack:** 13 = 709.93 < 48 = 711.06 < 200 = 713.73, price below all → **bearish stack**.
- **Confluence:** **PMH 714.96 + PDL 715.51** (0.08% apart) = the key resistance band (≈ ES 7194–7200, which also matches ES's overnight high 7199.25). **717.5–718.6 zone + 718 put node** above that. Below, **700** is the dominant magnet.
- **Game plan:** Reclaim and hold 715.5 on a 15-min close and calls toward 718 (zone + GEX node); lose the PML ~709 after 9:45 and puts toward 705, then the 700 wall. Anything between 709 and 715 is pre-market range, a no-trade zone.

### QQQ (pre-market ~633.3)
| Level | Price | Type | NQ ≈ |
|---|---|---|---|
| PDH | 675.16 | | 27876 |
| 15m zones | 646.7–647.8 (Tue/Thu lows) | resistance; **+ 646–647 GEX pivot** | 26700–26745 |
| **PDL** | **644.43** | **resistance**; Thu close 645.04 | **26607** |
| PMH | 641.82 (4:01) | **~0.3% from 640 put node** | 26499 |
| GEX | **640 put node (−0.70B)** | | 26424 |
| GEX pivot | 636–637 | | ~26260–26300 |
| PML | 633.00 (7:40) | | 26135 |
| GEX | **630 (−0.59B)** / 625 / 620 | magnets below | 26011 / 25805 / 25598 |
- **2-min EMA stack:** 633.95 < 635.15 < 639.49, price below all → **bearish**.
- **Confluence:** PDL 644.43 ≈ NQ 26607 lines up with NQ's overnight high 26603.5 and Thu settle ~26600 (strong resistance). 640 put node sits just under PMH 641.82 (slightly outside 0.2%). Below, **630** is the next big node (≈ NQ 26000 round number).
- **Game plan:** Break and hold above 641.8–640 (PMH/put node) on a 15-min close and calls toward 644.4 (PDL); lose 633 after 9:45 and puts toward 630, then 625.

### IWM (pre-market ~263.7)
| Level | Price | Type | RTY ≈ |
|---|---|---|---|
| PDH | 271.78 | | 2738 |
| 15m zones | 265.3 (Thu 13:15–14:00 lows) | resistance; **+ 265 put wall (−0.54B)** | 2670 |
| PMH | 264.82 (5:43) | | 2668 |
| **PDL** | **264.06** (Thu close 264.20; 264.0 15m low) | **resistance** | 2661 |
| PML | 263.11 (4:01) | **+ 263 put node (−0.30B)** | 2651 |
| GEX | 262 / 261 put nodes | | 2640 / 2630 |
- **2-min EMA stack:** 263.72 / 263.86 / 264.29, tightly bunched around price → **chop**, slight bearish tilt.
- **Confluence:** **265–265.3** (put wall + 15m zone, just above PMH). **263.0–263.1** (PML + 263 node). IWM is only ~0.1% under the PDL and the whole pre-market range is tight (263.1–264.8), so it's the cleanest no-trade box of the three.
- **Game plan:** Break 264.8–265.3 (PMH/wall/zone) on a 15-min close and calls toward 267 (pivots); lose 263.1 and puts toward 262, then 261.

### Bias framing (Team2Trading)
All three open below the PDL, so the PDL is **resistance**: a rejection there favors puts, and a 15-min close back above it plus a retest flips the bias. The pre-market range is a no-trade zone. Wait for a 15-min close beyond a level, nothing before 9:45 ET, and it's OPEX Friday, so trade light.

### History parallels
- Six straight down days + VIX ~30 + deep short gamma (SPY −20.2B at Thu close, second only to Oct 16's −28.9B) looks like my deep-negative-GEX file. Those readings came before sharp **snap-back rallies on a catalyst** (Jun 10 → Jun 11, Jul 29 → Jul 30, Oct 16), **but** only after the flush. Short gamma also let moves extend in both directions (Apr 8, Jun 5).
- Thursday's early put buying at the ask = continuation. The snap-back signal in my study (heavy put selling at the bid) is only faintly present (late IWM Dec put sales).

---

## Macro

**Calendar (ET), no 8:30 release today:**
- **8:25** Fed Gov. **Waller** (welcoming remarks, College Fed Challenge).
- **10:00** **UMich consumer sentiment (final Nov):** consensus ~51.0 (Econoday) to 52; preliminary 51.0; Oct final 48.0.
- **12:15** Fed Gov. **Cook** (U.S. economy in global context, Santiago).
- **1:00** Baker Hughes rig count.
- Next week: S&P Global flash PMIs **Mon Nov 23, 9:45**.
- **Monthly OPEX today.**

**Earnings:**
- **Before the open today:** BJ, MOG.A, FRO, IESC, MFG, BKE, BSP, RLX, WRD. None are index movers.
- **Thu after the close:** **INTU** cut FY27 revenue guidance (Credit Karma) and agreed to sell Mailchimp to Bending Spoons for ~$3.68B; −10–11% pre-market.
- Dell, CrowdStrike and Oracle are coming up (mentioned in X replies; dates not confirmed here).

**Overnight / Globex (Yahoo, to 7:30 ET):**
- **NQ:** 26152, ONH 26603.5 (18:00, the open) / ONL 26100 (7:30). It's grinding to new overnight lows into the US morning and gapping ~1.7% below Thu's settle.
- **ES:** 7137.25, ONH 7199.25 / ONL 7125.25 (7:30).
- **RTY:** 2657.3, ONH 2667.4 / ONL 2649.4 (22:10). Small caps are holding up relatively well.

**Global:**
- **Asia:** Nikkei −5.06% (56,437), Kospi −5.21%, Hang Seng −1.89%, Shanghai −1.22%.
- **Europe (7:30):** Euro Stoxx 50 −2.17%, DAX −2.04%, CAC −1.44%, FTSE −0.80%.
- Chip stocks are falling worldwide.

**Volatility:** VIX 30.52 (ONH 30.54), above 30 for the first time since March. Fear tone, backwardation chatter on X.

**Cross-asset:**
- **10-year 4.98%**, under 5% and down >13 bp this week on a flight to bonds (FXStreet, ~7:33 ET).
- **DXY** 103.81 (−0.09%).
- **WTI** 82.27 (−1.13%), **Brent** 89.35 (−2.86%).
- **Gold** 3572.4 (−3.07%): it's being sold alongside stocks, a liquidation tone.

**Financial Juice (overnight):**
- **Yemen's Houthis threaten Saudi Red Sea ports** (Jeddah) and the Shugaiq power plant (6:17–6:58). Energy/geopolitical tail risk, yet oil is down.
- Russian strikes on Kyiv overnight. Russia says there's no agreement on the next round of Ukraine talks.
- UK–EU summit deal concluded.
- German PPI 8.1% y/y (vs 7.3% expected). UK retail sales beat (+0.7% m/m vs 0%).
- Traders pare ECB hike bets to two by end-2027.
- FT: China preparing to resume US private-equity investments.

**X market news:**
- S&P's six-day losing streak; it's >8% below the early-Oct record.
- Citi: ~95% of $45.9B in S&P futures longs are underwater.
- Tech forward P/E at 16.4x, a pandemic-low valuation.
- NVDA near $149 lows after the Nov 12 CEO change.
- Report on ~880k H200/MI325X chips approved for Chinese firms (Dec 2025–May 2026).
- Hunterbrook-linked report on AMD/China ties (FXStreet).

---

## Takeaway (information, not advice)
- **Key confluence resistance:**
  - **SPY 715.0–715.5** (PMH + PDL; ≈ ES 7194–7200, ES's ONH)
  - **QQQ 644.4** (PDL; ≈ NQ 26600, NQ's ONH/settle)
  - **IWM 265.0–265.3** (PMH area + put wall + 15m zone)
- **Downside magnets:** **SPY 700** (−2.26B, the dominant node; ≈ ES 7044), **QQQ 630** (≈ NQ 26000), **IWM 263 → 262**.
- Deep short gamma + VIX 30 + OPEX expiry means big ranges in both directions. Six-day streaks into deep negative GEX have come before violent snap-backs in my history, but only after the flush. Let a 15-min close after 9:45 decide, and size light on OPEX.

