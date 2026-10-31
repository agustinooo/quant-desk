# Pre-Market Brief, Thu Oct 29, 2026 (data as of ~8:10 AM ET)

Tech-led gap down: GOOGL is off 10-11% pre-market on weak search revenue and -$9.07B free cash flow, while MSFT is up 2-4% on Azure +48%. NQ is -1.2%, ES -0.4%, and RTY is slightly green. Big 8:30 print: Q3 GDP plus September PCE. AMZN and INTC report after the close. Not a Friday or monthly opex (tomorrow is Friday weekly expiry plus month-end). Casey (@Team2Trading) last night on FOMC day: "No trades for me today... this chart was as ugly as they come."

## Positioning (Quant Data API on the user's account, ~8:10 AM ET; pre-market GEX is a thin first read. Heatmap nodes not pulled separately, so GEX by strike is the magnet proxy)
- SPY: net GEX -5.84B, negative gamma (Wed close was +2.08B with a 772 0DTE pin, now expired). Call walls 800, 780, 775. Put walls 765 (largest, -1.89B), 760, 750. No cumulative flip; nearest sign change 772. Dark pool: 769.7 (~$2.48B, the dominant print), 772.3 ($0.54B).
- QQQ: net -4.59B, negative gamma. Call walls 740, 750, 730. Put walls 700 (largest), 710, 690. Nearest sign change 726. Dark pool 721.2 ($0.77B), 722.0-722.4.
- IWM: net +0.66B, the only positive one. Call walls 284, 283, 282; cumulative flip 284; sign change 282. Put gamma 278, 275. Dark pool 280.0-280.4.
- 9,000+ contract prints, Wed Oct 28 (141 total, no SPY). None so far this pre-market.
  - QQQ Nov 6 680P 20,000 at the bid ($3.4M, 13:35), then Nov 20 680P 28,000 at the ask ($13.5M, 13:39). A roll out in time: protection kept, not removed.
  - QQQ Dec 18 780C/800C, 15,000 each, 10:16, same timestamp. An upside call spread.
  - IWM Nov 20 268P/266P, 56,998 each, 16:06 (after the close), 268 at the ask and opening. A put-spread hedge.
  - IWM Dec 18 240P 23,592 above the ask ($2.24M, 12:00) and Jan 15 265P 10,000 at the ask ($4.56M). Tail hedges. IWM Dec 18 270P 10,000 at the bid ($4.11M) was sold.
  - IWM Oct 30 283C/284C (16,000 and 22,000, 14:25), opening. A call spread into tomorrow sitting right on the 283-284 call walls and flip.
  - IWM Oct 29 280C 9,375 above the ask ($1.74M, 10:26). A 0DTE for today, now in the money.
  - VIX Nov 18 26C 12,759 at mid; VIX Nov 18 15P/16.5P put spread. HYG put spreads all day (mixed bid/ask), TLT Dec 31 79P/75P opening (a bet on higher yields), XLF 54P Jan/Jun calendar. SPX $0.05 deep-OTM puts are noise.
  - Read: hedges are being rolled and added (QQQ, IWM), not unwound, ahead of mega-cap earnings. That doesn't look like a sweep-reversal signal. With SPY and QQQ now in negative gamma, moves can extend once levels break. The study's note applies: short-dated put buying into an event tended to precede whipsaws, and a lack of big prints didn't mean calm.

## Combined levels map (PM range 4:00 AM to ~8:10 AM ET, can still change before 9:30)
Ratios: ES ~10.08x SPY, NQ ~41.35x QQQ, RTY ~10.10x IWM. Futures levels are approximate.

**SPY** (PM last 768.84, opening below the PDL, so it becomes resistance)
- PDH 773.36 (ES ~7795), PDL 769.24 (ES ~7754), PDC 772.35.
- PMH 771.39 (ES ~7776), PML 768.48 (ES ~7746; the ES overnight low is 7740).
- 2-min EMA stack 13/48/200: 769.22, 769.90, 770.08. Bearish stack (13 under 48 under 200).
- Confluence:
  - 769.2-770.1 is the key lid: the PDL, the $2.48B dark pool at 769.7, and the 48/200 EMAs.
  - 772-772.4: PDC, the 772 sign change, and dark pool 772.3.
  - 765.2: the Oct 27 low on the 765 put wall (largest), ES ~7713.
- Untested zone: 767.7 (Oct 26 high) as first support.
- Game plan: reclaim 769.7 with a 15-min close and calls toward 771.4, then 772.4. Lose 768.5 and puts toward 767.7, then 765 (put wall).

**QQQ** (PM last 716.40, gap -1.25% under the PDL)
- PDH 726.12 (NQ ~30025), PDL 720.30 (NQ ~29784), PDC 725.48.
- PMH 720.18 (NQ ~29779; the NQ overnight high is 29794). PML 714.98 (NQ ~29565).
- EMA stack: 716.84, 717.67, 718.46. Bearish.
- Confluence:
  - 720.2-721.2 is a heavy lid: PMH, PDL, and the $0.77B dark pool at 721.2.
  - 715.0-715.3: the PML plus the Oct 26 high.
  - 713.6: the Oct 27 low (NQ ~29507, near the 29482 overnight low).
  - 710 put wall (NQ ~29358).
- Game plan: a 15-min close back above 720.3 and calls toward 721.2, then 725.5-726 (PDC/sign change). Lose 715 and puts toward 713.6, then 710 (put wall).

**IWM** (PM last 281.75, above the PDH; relative strength)
- PDH 281.48 (RTY ~2842), PDL 279.05 (RTY ~2817), PDC 281.29.
- PMH 283.29 (RTY ~2860, matching the 2860.8 overnight high). PML 281.61.
- EMA stack: 281.85, 282.18, 282.01. Bunched, so chop.
- Confluence:
  - 281.5-282: PDH, PML, and the 282 call wall/sign change. Support if it holds.
  - 283.3-284: PMH, 283/284 call walls, the cumulative flip, and Wed's 283/284 call spread.
  - 280.0-280.4: dark pool cluster.
- Opening above the PDH turns it into support (break and retest).
- Game plan: hold 281.5 and a 15-min close above 283.3, calls toward 284. Lose 281.5 and puts toward 280.1, then 279.05 (PDL).

Bias framing: the pre-market range is a no-trade zone. Wait for a 15-minute close beyond a level, nothing before 9:45. SPY and QQQ opening under the PDL makes it resistance (look for rejection there or a reclaim-and-hold). 8:30 data can reset the pre-market range.

## Macro
- Calendar (ET; consensus from Tuesday's compiled sources, may have shifted):
  - 8:30: Q3 GDP advance (consensus ~3.0-3.2% across sources, prior 2.2%). September PCE: core m/m +0.3% (prior +0.2%), core y/y 3.1% (prior 3.0%; Yahoo confirms 3.1%). Personal income +0.3%, spending +0.3%. Jobless claims 196K (prior 194K).
  - 1:00 PM: 7-year auction.
  - Fed speakers: not checked this morning.
  - Tomorrow: 8:30 Q3 ECI, 9:45 Chicago PMI, BoJ decision, weekly expiry plus month-end.
- Earnings:
  - Wed after the close: GOOGL -10 to -11% (13 price-target cuts), MSFT +2-4% (plus a $25B+ bond sale today), NOW -13% and FTNT -22% (Wed after hours).
  - This morning: LLY big beat (revenue $24.40B vs $22.52B, FY raised to $91-92B). MA beat ($5.31 vs $5.17). BMY beat. HSY beat and raised. MO in line and raised. DHI's 2027 guide is below estimates. CAT and MRK reported (numbers not pulled). DASH is buying CART at $65/share.
  - After the close today: AMZN, INTC.
- Headlines (Financial Juice and X squawks overnight):
  - IRGC Navy says 3 tankers caught fire after hitting mines off the Strait of Hormuz.
  - Semafor says the Trump administration is in talks on a temporary peace deal.
  - North Korea launched about 10 missiles.
  - ECB's Lagarde will step down Feb 7, 2027.
  - BofA now sees Fed hikes in December and March.
  - NYT says a suspected US spy helped China evade AI chip curbs. China protested new Xinjiang entity listings. The yuan is at its strongest since 2022.
  - Silver -3% to $52.40.
- Globex (~8:00 AM ET vs Wed settle):
  - NQ 29620.75 (-1.2%), overnight range 29482.5-29794.25.
  - ES 7749.75 (-0.4%), 7740-7773.75.
  - RTY 2844.3 (+0.2%) sits at its overnight low, 2843.9-2860.8.
- Global: Nikkei +1.1% (64,659). KOSPI -1.2%, Shanghai -0.8%, Hang Seng -0.6%. Europe firmer: DAX +0.7%, CAC +0.7%, FTSE +0.3%, Stoxx 50 flat.
- Vol and cross-asset: VIX 17.13 (+0.22). 10-year 5.05% (Wed close, live not pulled). DXY 102.22. WTI 101.96 (-0.8%). Gold 4032 (-0.5%).

## History
This resembles past gap-down mornings in negative gamma, where moves extended once levels broke. At -5.8B SPY GEX it's nowhere near the -15B to -23B extremes that came before the cleanest snap-backs. There's no heavy put selling at the bid yet; the flow is hedge rolls and adds instead.

## Takeaway (information, not advice)
The magnets that matter:
- SPY 769.2-770.1 (PDL, dark pool, EMAs) as the lid, 765 put wall below.
- QQQ 720.2-721.2 (PMH, PDL, dark pool) as the lid, 715 then 713.6 and the 710 put wall below.
- IWM 281.5-282 support and 283.3-284 call wall/flip resistance.
Negative gamma in SPY and QQQ means the 8:30 data and the open can push moves further than usual. IWM's positive gamma and relative strength point to a rotation day rather than a broad flush.
