# Williams Trading System — Quick Start for Chris

## What This Is

A complete Larry Williams trading methodology built into two interactive tools, synthesized from his **Forecast 2026** annual report (128 pages) and decades of his published strategy.

**Live Links:**
- **2026 Forecast + Stock Dashboard:** https://yarmoluk.github.io/williams-trading-system/williams-forecast-2026.html
- **Live Indicator Dashboard:** https://yarmoluk.github.io/williams-trading-system/

---

## The Two Tools

### 1. Williams Forecast 2026 (`williams-forecast-2026.html`)

Toggle between two views:

**METHODOLOGY** — 8 slides explaining Williams' logic:
- 4-year cycle (60+ years out of sample, 2026 = buy year)
- Decennial pattern (years ending in 6 rally Jul-Nov)
- Presidential cycle (2nd year: March peak → summer low → massive rally)
- Natural cycle (bullish from late April through August)
- Fundamentals (no recession until mid-2027, rates declining, early inflation = bullish)
- **The Playbook:** cautious Jan-Feb → accumulate Mar-Jun → ride Jul-Dec

**DASHBOARD** — 71 tickers with:
- Cycle confidence scores (from Williams' own charts)
- Current phase as of today
- Sweet spot timing (when the strongest wave starts)
- Filter by category, search by ticker, sort any column
- Color-coded: green 90%+, yellow 70-79%, orange <70%

### 2. Live Trading Dashboard (`index.html`)

Real-time simulation of Williams' indicator stack:

| Layer | Indicator | What It Does |
|-------|-----------|-------------|
| L1 | COT Index | Directional bias from commercial positioning (smart money) |
| L2 | Seasonal | Historical win rate for current month |
| L3 | Williams A/D | Accumulation vs distribution (price-only, no volume) |
| L4 | Williams %R | Entry trigger via failure swing method (not simple OB/OS) |
| L4 | Ultimate Oscillator | Entry trigger via 3-timeframe divergence |
| L5 | Pattern Detection | OOPS!, Smash Day, Inside Day, Outside Day, Volatility Breakout |
| L6 | Position Sizing | Fixed fractional 2% risk per trade |

The **Confluence Engine** scores 0-100 based on how many layers align. The hierarchy banner at top shows Williams' actual decision flow.

---

## Williams' 2026 Playbook (The Short Version)

```
PHASE 1: Jan-Feb     → Market tops. Be cautious.
PHASE 2: Mar-Jun     → Decline. BUY THE DIP. Target low: ~June 16.
PHASE 3: Jul-Dec     → Major rally. Hold. "Powerhouse prices from May onwards."
```

**We are in Phase 2 right now.** The cycle says the decline from mid-February has begun. This is the accumulation window.

---

## Key Williams Rules

1. **Cycles tell you WHEN, not HOW FAR.** Use them for timing, not price targets.
2. **Buy market breaks.** When cycles say "low coming," buy the dip — don't try to pick the exact bottom.
3. **No single indicator is a system.** Layer COT + seasonal + A/D + trigger + pattern for high-probability entries.
4. **Failure swings > simple overbought/oversold.** Don't just buy because %R hit -80. Wait for the failure swing confirmation.
5. **2% max risk per trade.** Stop at the prior swing point. Position size = (Account × 0.02) / (Stop distance × point value).
6. **Hold winners.** "You will never make big money until you learn to hold on to your winners."
7. **Exit at UO > 70** (longs) or **UO < 30** (shorts), or when a new signal fires the other direction.

---

## Top Confidence Stocks (90%+)

These had the highest cycle wave confidence in Williams' 2026 report:

| Ticker | Name | Confidence |
|--------|------|-----------|
| DJIT | DJ Islamic Titans | 96% |
| SBUX | Starbucks | 93% |
| BRK-B | Berkshire Hathaway | 90% |
| COST | Costco | 90% |
| DAL | Delta Air Lines | 90% |
| GOOG | Alphabet | 90% |
| MSTR | Strategy (MicroStrategy) | 90% |
| RITM | Rithm Capital | 90% |
| Brazil | Bovespa Index | 90% |

---

## How to Use This Week

1. **Open the Forecast Dashboard** → toggle to DASHBOARD → sort by Confidence (descending)
2. **Filter to stocks you already trade** or are interested in
3. **Check sweet spot timing** — if the strongest wave hasn't started yet, you're early (good)
4. **Cross-reference with the Live Dashboard** → are the indicators confirming? Is %R oversold? Is A/D showing accumulation?
5. **Size your position** using the 2% rule before entering

---

## What's Simulated vs Real

- **Simulated:** The live indicator dashboard uses generated price data to demonstrate the indicators. It's a teaching tool, not live market data.
- **Real from Williams:** All cycle confidence percentages, timing projections, phase descriptions, and stock selections come directly from his Forecast 2026 report.
- **To connect to real data:** Would need to integrate a market data API (Alpha Vantage, Polygon, etc.) — a future build if you want it.

---

## Disclaimer

Based on Larry Williams' Forecast 2026 (Copyright 2025 LNL Publishing, LLC). Cycle projections are probabilistic, not guarantees. Past performance does not indicate future results. All trading decisions are your own. Use only risk capital.
