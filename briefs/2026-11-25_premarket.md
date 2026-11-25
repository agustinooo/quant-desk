# Pre-Market Brief, Wed Nov 25, 2026 (data as of ~7:45 AM ET)

**Gap down into deeper short gamma ahead of 8:30 PCE/GDP.** NQ is down ~2.9% overnight. It's a chip/AI rout plus a WSJ report that the White House is preparing broad tariffs on 16 economies (China, EU, Japan, Korea, India, Vietnam, Mexico) after the USTR subsidy probe (X News).
- **Futures (Yahoo, 7:35 ET, ~10 min delayed):**
  - **NQ 25522 (−2.87%)**, ON range 25470.5 (07:05) to 26350.75 (18:05)
  - **ES 7077.5 (−1.94%)**, ON 7069.5 (07:20) to 7224 (18:00)
  - **RTY 2653.4 (−1.33%)**, ON 2650.2 to 2690.1
  - All three are sitting near their overnight lows.
- **Chips are leading down** (pre-market):
  - NVDA 147.10 (−5.3%), MU −6.3%, AMD −5.5%, ORCL −5.2%, SMH −4.6%, AVGO −4.3%, CRWV −6.7%
  - MSFT/GOOGL −3.4%, AMZN −3.1%, TSLA −2.6%, META −2.3%, AAPL −0.9%
- **VIX 30.73 (+16.6%)**, ON high 31.09.
- **Gamma is more negative across the board (Quant Data):**
  - **SPY −6.07B** (from −3.43B yesterday AM)
  - **QQQ −2.57B** (from −1.59B)
  - **IWM −0.79B**
  - Dealers are short gamma, so moves can extend both ways, and the 8:30 data hits a thin, holiday-shortened tape.
- **All three are opening BELOW Tuesday's low** (SPY PDL 712.14, QQQ 631.15, IWM 263.97). In Casey's framework, the PDL is now resistance.
- **Not a Friday and not monthly OPEX**, but it's the day before Thanksgiving: markets are closed Thursday and close at 1 PM Friday. Expect thin liquidity.

**Sources:**
- Quant Data API on your account (GEX by strike, dark pool, 9k+ unconsolidated flow for Tue plus today's pre-market, 7:45 ET)
- Yahoo Finance (1m/2m/15m/daily bars, futures, global, cross-asset)
- Financial Juice RSS
- X News
- TD Economics/Bloomberg consensus table

**Caveats:**
- Positioning comes from the API, not the browser My Pages. The 'contract flow' Session Date wasn't touched (still May 29, 2026), and no filters were added.
- There's no heatmap or interval-map read, so the "magnets" are the largest GEX nodes and dark-pool levels.
- No cumulative gamma flip shows near spot. The pivots listed are per-strike sign changes.
- Futures translations are approximate: ES ≈ SPY×10.04, NQ ≈ QQQ×41.16, RTY ≈ IWM×10.06.

---

## Positioning (Quant Data, 7:45 AM ET)

**SPY** (spot 705.10)
- **Net GEX −6.07B** (all) / −5.35B (ex-0DTE). Deep short gamma.
- **Put walls:** **700 (−0.76B)**, 675 (−0.68B), 690 (−0.65B), 680 (−0.60B), 650 (−0.41B).
- **Call walls are far:** 730 (+0.10B), 750 (+0.11B), 800 (+0.19B).
- **Per-strike pivots:** 721 (all), and 717–718 / 721 / 724–725 (ex-0DTE).
- **Dark pool:** the largest print today is **704.42**, then 704.68. Overhead are 711.46 and 713.58.

**QQQ** (spot 620.01)
- **Net GEX −2.57B** (all) / −2.03B (ex-0DTE).
- **Put nodes:** **600 (−0.41B)**, **610 (−0.39B)**, **620 (−0.34B, at spot)**, 635 (−0.29B), 605 (−0.28B).
- **Call walls:** 660–700. These are far above.
- **Per-strike pivots:** **622–625** (ex-0DTE), 637 (all).
- **Dark pool:** the heaviest prints are overhead at **628.4–629.7**, plus 624.55. Near spot, prints sit at 619.5–620.7.

**IWM** (spot 263.75)
- **Net GEX −0.79B**.
- **Put nodes:** 250 (−0.13B), **267 (−0.11B)**, **265 (−0.08B)**, 255, **263 (−0.06B)**.
- **Calls are tiny:** 269 and 285+.
- **Pivot:** 269.
- **Dark pool:** 263.31–263.55, plus 265.2.

### 9,000+ contract flow
**Pre-market today (to 7:45): none.**

**Tuesday Nov 24: 140 prints across all tickers.** Index and mega-cap highlights below (times ET):
- **SPX 11:12:** opened 6500P 4/16, 11,000 contracts above the ask, **$192M**. That's a large, longer-dated tail hedge bought outright (SPX was 7152).
- **SPY 13:44, hedge rolled out in time:**
  - Closed 610P/480P/350P 12/18 (150k/300k/150k at the bid).
  - Opened **615P and 480P 2/19, 150,000 each below the bid** ($103M + $26M).
  - Same-timestamp, so it's a structural roll of a put-spread hedge, not a directional bet.
- **SPY 13:58:** opened 700P 12/11 (10,050 at ask) and closed 675P. That's a hedge rolled up, and it fits **700 being SPY's #1 put wall**.
- **QQQ 15:30:** closed deep-ITM **720P/725P 12/18, 12,000 each at the ask (~$213M)**. These are deep-ITM closing trades and say nothing about direction.
- **QQQ restructures:**
  - 11:02: closed 690C, opened 510P, and closed 605P 12/18 (15,750 each). That's a collar/hedge restructure.
  - 15:35: closed 625P/650C 12/18 (10k).
  - 16:12: closed 580P 12/18.
- **NVDA 9:49:**
  - Closed Monday's tail puts (80P 1/15, 120P 1/15 and 2/19).
  - Opened 90P 5/21, 75,000 at the bid (~$18M), likely put selling.
- **VIX:** a series of closes in puts (16–20 strikes) and calls (20–40 strikes). Vol traders were flattening, not adding.
- **IWM:**
  - Put rolls/closes in 252–258 for 12/4 and 12/18.
  - At 15:50, opened 280C 1/15, 10,000 at the bid (likely call selling).

**Read:**
- Tuesday's big prints were mostly **adding and extending protection** (SPX 6500P bought, SPY hedge pushed to Feb, SPY 700P rolled up), plus closing deep-ITM QQQ puts.
- There was **no heavy bid-side put selling in the index ETFs**. That's the pattern your study tied to the cleanest snap-backs (Jun 10→11, Jul 28→30), and it isn't there yet.
- SPY −6B is negative, but well short of the −15B to −29B extremes in gex_before_moves.md. Most big moves in that sample started in negative gamma, in either direction.

---

## Combined levels map (Team2Trading + GEX)
PM high/low are 4:00 AM to 7:45 AM ET and can still change before 9:30. PDH/PDL are Tuesday's RTH levels.

### SPY (pre-market ~705.0 | ES ~7078)
- **PDH 720.93 / PDL 712.14** (close 718.78)
- **PMH 714.24** (04:01) / **PML 703.90** (07:34)
- **2-min EMA stack:** 13 = 705.05 < 48 = 705.83 < 200 = 710.31. **Bearish.**
- **15-min zones:**
  - 703.98 (Nov 20 rejection)
  - 699.01 (Nov 20 support)
  - 686.75 (Nov 20 low, untested)
  - Overhead: 711.7–712.4 (Nov 20 / Nov 24 supports, now resistance)
- **Confluence:**
  - **703.9–704.4:** PML + 704.42 largest dark pool + Nov 20 703.98 pivot (ES ~7068–7073).
  - **699–700:** 700 put wall + Nov 20 699.01 support (ES ~7018–7028).
  - **711.5–714.2:** PDL 712.14 (now resistance) + dark pool 711.46/713.58 + PMH 714.24 (ES ~7143–7171).
- **Bias:** opening under the PDL means 712 is resistance. Inside 703.9–714.2 is the PM range, so no trades there. Wait for a 15-minute close and take nothing before 9:45.
- **Game plan:** lose 703.9 on a 15m close and puts toward 700 (put wall), then 690. Reclaim and hold 714.2 and calls back toward 718–721 (pivots/PDH).

### QQQ (pre-market ~620.0 | NQ ~25520)
- **PDH 648.00 / PDL 631.15** (close 638.10)
- **PMH 626.42** (04:06; a single 631.00 print at 04:01 was filtered out) / **PML 618.43** (07:21)
- **2-min EMAs:** 13 = 619.87 < 48 = 620.49 < 200 = 626.50. **Bearish**, with the 13/48 bunched at price.
- **15-min zones:**
  - 618.72 (Nov 20 support)
  - 625.22 (Nov 20 rejection)
  - **606.23** (Nov 20 low, untested)
- **Confluence:**
  - **618.4–620:** PML + Nov 20 618.72 + 620 put node + dark pool 619.5–620.7 (NQ ~25455–25520).
  - **624.5–626.4:** PMH + 625.22 rejection + 622–625 GEX pivots + 624.55 dark pool (NQ ~25705–25785).
  - **605–606.2:** Nov 20 low + 605 put node, with 610 above and 600 below (NQ ~24900–24950).
  - Overhead is the 628.4–629.7 dark-pool shelf, then the PDL at 631.15 (NQ ~25980).
- **Game plan:** lose 618.4 and puts toward 610, then 605–606 (put nodes + Nov 20 low). Break and retest 626.4 and calls toward 629–631 (dark pool / PDL as resistance).

### IWM (pre-market ~263.7 | RTY ~2653)
- **PDH 268.31 / PDL 263.97** (close 267.14)
- **PMH 266.34** (04:01) / **PML 263.31** (07:21)
- **2-min EMAs:** 263.67 < 264.00 < 265.27. **Bearish.**
- **15-min zones:**
  - 263.85 (Nov 23 support)
  - 262.62 (Nov 20)
  - 260.93 (Nov 20 rejection)
  - 258.98 (Nov 20)
  - 256.32 (Nov 20 low)
- **Confluence:**
  - **263.3–263.55:** PML + dark pool + 263 put node (RTY ~2649–2651).
  - **263.85–264.0:** PDL + Nov 23 support, now resistance (RTY ~2655).
  - **265–265.3:** 265 put node + dark pool 265.2 + Nov 19 pivots.
- **Game plan:** lose 263.3 and puts toward 262.6, then 261. Reclaim 264 on a 15m close and calls toward 265–266.3 (node / PMH).

**Setup echo:** this looks like Nov 20, when deep negative gamma and a chip-led selloff ran SPY to 686.75, QQQ to 606.23 and IWM to 256.32. Those Nov 20 lows are the untested downside magnets today if the 700 / 610 put walls give way.

---

## Macro
### Calendar (ET; consensus from Bloomberg/TD and X News)
- **8:30:**
  - **October PCE:** headline +0.3% m/m, 3.8% y/y. **Core +0.3% m/m, 3.2% y/y.**
  - **Q3 GDP second estimate:** 3.4% (prior 3.4%)
  - **Personal income:** 0.3% (prior 0.2%). **Real spending:** 0.0% (prior 0.0%).
  - **Durable goods:** +0.5% (prior +1.9%)
  - **Initial claims:** ~200–201k (prior 203k)
- **10:00:** new home sales, 648k (prior 676k)
- **14:00:** Fed Beige Book
- **Fed:** X News says prediction markets price ~97% odds of a **25bp hike** in December. A hot PCE adds to the hike pricing. I didn't confirm a Fed speaker schedule for today.
- Already out: MBA mortgage apps +6.1%, with the 30-year at 7.38%.

### Earnings
- **DELL (last night):** revenue $54.9B vs $49.3B expected, AI orders $60.2B, backlog $132.3B, FY revenue raised to $202B (X News). Today's stock reaction isn't in my pull.
- **AMBA −40%** on a miss and weak guidance, which cited memory costs.
- No major index movers before the open today.

### Headlines (Financial Juice / X, overnight to now)
- **Tariffs:**
  - WSJ: broad tariffs are being prepared on 16 economies (X News).
  - China says "overcapacity does not exist" (02:13).
  - China's Zhu says 301 tariffs can be settled by talks, with a "new chapter" in January (01:27–01:30).
- **NVDA:**
  - The rally keeps unwinding, with Congressional scrutiny of Huang.
  - Reports on financing by firms linked to Huang's family.
  - Gaming GPU allocations cut 20–30% (X News).
- **Asia AI rout (X News):** ~$750B wiped out. Taiex fell 8.6% intraday and closed about −5%, and SoftBank dropped more than 10%.
- **Hormuz/Red Sea:**
  - IRGC says two tankers are ablaze on an unauthorized route (23:42).
  - Saudi coalition struck Hodeidah, and the Houthis threaten Jeddah (17:15–21:44).
- **Global inflation is hot:**
  - Australia CPI 4.9% vs 4.7% expected (19:30).
  - Japan services PPI 4.2% vs 3.6% expected.
  - ECB's Kocher: "shouldn't fall behind the curve," with the inflation outlook likely revised up.
- **OpenAI:** ChatGPT errors for Team/Business/Pro (07:03).

### Global and cross-asset (Yahoo)
- **Asia:**
  - Kospi −6.2%
  - Nikkei −2.8%
  - Shanghai −2.0%
  - Hang Seng −1.1%
- **Europe:**
  - Euro Stoxx 50 −0.6%
  - DAX −0.4%
  - FTSE −0.1%
  - CAC +0.5%
- **VIX 30.73.**
- **10-year 4.90%** (Tuesday close; no fresh print yet).
- **DXY 103.96 (+0.1%).**
- **WTI 82.40 (+0.4%)**. Brent 89.02 (−2.6% vs the 91.40 settle).
- **Gold 3553 (−0.3%).**

---

## Takeaway (information, not advice)
- **It's a chip- and tariff-led gap below Tuesday's lows into deeper short gamma (SPY −6.1B), with PCE/GDP at 8:30 and holiday-thin liquidity.** Moves off levels can extend.
- **The key confluence levels:**
  - **SPY:** 703.9–704.4 (PML + biggest dark pool + Nov 20 pivot; ES ~7070), the **700 put wall** (ES ~7028), and 712–714 overhead (PDL turned resistance + PMH; ES ~7150–7171).
  - **QQQ:** 618.4–620 (PML + 620 put node; NQ ~25455–25520), 624.5–626.4 (PMH + GEX pivots; NQ ~25705–25785), then **610 / 605–606** (put nodes + Nov 20 low; NQ ~24900–25110).
  - **IWM:** 263.3–263.5 support and 264 (PDL) resistance.
- **Tuesday's big flow was hedging, not capitulation.** There's no bid-side index put selling yet.
- **The PM range is a no-trade zone. Wait for 15-minute closes, and take nothing before 9:45.**
