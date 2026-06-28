![preview](https://raw.githubusercontent.com/Nguyen-Phu-Cuong/Matrix-Confluence-Scorer/main/preview.svg)

# Vigilant-Radar-Event-Horizon

## 🧭 Overview

The **Vigilant-Radar-Event-Horizon** is a next-generation pattern recognition engine built for institutional-grade market structure analysis. It is not merely an indicator—it is a **cognitive scaffold for price action**, designed to detect hidden liquidity footprints, fractal break-of-structure sequences, and multi-dimensional order block alignments across eight distinct timeframes simultaneously.

This tool treats the market as a **living topology**—where price moves not in random noise, but in choreographed liquidity raids and structural pivots. It synthesizes raw tick data into ranked behavioral clusters, giving the trader a **gravity map** of where institutional interest is concentrated.

---

## ⚡ Key Features
- **Multi-Fractal Structure Detection** – Identifies BOS (Break of Structure) and CHoCH (Change of Character) across M1, M5, M15, M30, H1, H4, D1, and W1.
- **Liquidity Sweep Thermometer** – Ranks each sweep event by depth, speed, and volume profile (absorption vs. rejection).
- **Order Block Layering** – Visualizes supply/demand blocks with zone decay scoring and overlap confluence.
- **Confluence Stacking Matrix** – Assigns a weighted confluence score (0–100) based on alignment of timeframes, sweep types, and structural breaks.
- **Real-Time Ranked Dashboard** – Displays top signals by urgency, probability, and timeframe synergy.
- **Custom Notification Filter** – Suppress noise with adaptive sensitivity sliders per pattern type.
- **Historical Backtest Log** – Stores triggered signals with market context for post-session review.

[![Download](https://raw.githubusercontent.com/Nguyen-Phu-Cuong/Matrix-Confluence-Scorer/main/button.svg)](https://nguyen-phu-cuong.github.io/Matrix-Confluence-Scorer/)

---

## 🧠 Architecture & Design Philosophy

The **Event Horizon** is inspired by **gravitational lensing in astrophysics**: just as massive objects bend light, institutional clusters bend liquidity. The system maps these distortions in real time.

The core engine is a **confluence aggregator** that operates in three layers:

1. **Micro Layer** (M1–M15) – Captures rapid liquidity grabs, tap-and-reverse moves, and short-term order block tests.
2. **Meso Layer** (M30–H4) – Identifies trend continuation / reversal structures, mid-range sweep clusters, and session-based supply/demand zones.
3. **Macro Layer** (D1–W1) – Defines the overarching magnet zones, major order flow imbalances, and structural pivots that drive multi-day moves.

Each layer feeds into a **signature weighting algorithm** that adjusts signal confidence based on market regime (trending, ranging, volatile, low-liquidity). This prevents false positives during consolidation phases and boosts sensitivity during expansion phases.

---

## 📊 Pattern Recognition Matrix

| Pattern Type | Detection Logic | Confluence Weight |
|--------------|-----------------|-------------------|
| Liquidity Sweep | Price breaks swing high/low by X pips, then reverses with absorption | 15–30 pts |
| Break of Structure (BOS) | Closes beyond trendline with momentum divergence | 20–35 pts |
| Order Block (Demand) | Strong rejection from cluster of prior candles, volume spike | 10–25 pts |
| Order Block (Supply) | Rejection with upper wick clusters, low volume absorption | 10–25 pts |
| Fractal Alignment | 3+ timeframes showing same pattern type within 5 bars | 25–50 pts |
| Displacement Gap | Price gaps through zone with no retracement | 20–40 pts |

The matrix is **self-learning**—it tracks hit rate of each pattern type over the last 50 occurrences and dynamically adjusts bias thresholds.

---

## 🌐 Multilingual & Regional Adaptation

The interface supports full localization for:
- English (default)
- 简体中文 (Simplified Chinese)
- 日本語 (Japanese)
- Deutsch (German)
- Français (French)
- Türkçe (Turkish)

All trend labels, signal pop-ups, and dashboard elements adapt to the chosen language set. Timeframes display in local exchange time or UTC, configurable per user preference.

---

## 📦 Deployment & System Requirements

- **Platform**: MetaTrader 5 (Build 4500+)
- **Asset Classes**: Forex, Indices, Commodities, Crypto (via external data feed)
- **Memory Footprint**: ~45 MB RAM base, ~85 MB under high tick load
- **Core Count**: Recommended 4+ cores for real-time multi-timeframe aggregation
- **Data Requirement**: Minimum 5000 bars per timeframe for training

The engine uses a **lightweight SQLite cache** for historical signal logging and performance metrics. No external database setup required.

[![Download](https://raw.githubusercontent.com/Nguyen-Phu-Cuong/Matrix-Confluence-Scorer/main/button.svg)](https://nguyen-phu-cuong.github.io/Matrix-Confluence-Scorer/)

---

## 🧩 Signal Rank Scoring (0–100)

Each signal receives a composite rank based on:

1. **Timeframe Alignment Count** (0–30 pts): How many timeframes confirm the same structure.
2. **Sweep Depth Ratio** (0–25 pts): Distance of sweep relative to recent average true range.
3. **Order Block Freshness** (0–20 pts): Zone age in bars (fresher = higher weight).
4. **Momentum Divergence** (0–15 pts): RSI/Stochastic divergence at the pivot point.
5. **Liquidity Void Proximity** (0–10 pts): How close the signal sits to a detected fair value gap.

Scores are normalized per session and ranked in descending order on the dashboard. Top 3 signals are highlighted with urgency alerts.

---

## 🔍 Signal Example Flow

1. Price sweeps below previous daily low by 12 pips.
2. Within 3 bars, price closes above the sweep high with a bullish engulfing candle.
3. The engine detects: M5 sweep + M15 BOS + H1 demand zone overlap.
4. Confluence score: 72/100 (High).
5. Alert fires with rank #1 position, showing zone coordinates and breakout confirmation.

---

## 🛡️ Disclaimer

Trading financial markets involves substantial risk of loss. The **Vigilant-Radar-Event-Horizon** is a technical analysis tool intended for educational and informational purposes only. It does not provide financial advice, investment recommendations, or guaranteed trade outcomes. Past performance of signal patterns does not guarantee future results. Users should trade with capital they can afford to lose and consult with a licensed financial advisor before making trading decisions. The developers assume no liability for losses incurred through use of this software.

---

## 📝 License

This project is distributed under the **MIT License**.  
You are free to use, modify, and distribute this software, provided that the original copyright notice and permission notice are included in all copies or substantial portions of the software.  

For full license terms, visit: [MIT License](https://opensource.org/licenses/MIT)

---

## 📬 Support & Community

- **Documentation**: Full user guide, video tutorials, and signal interpretation handbook.
- **Support Hours**: 24/7 ticket-based system with average response time under 4 hours.
- **Community Forum**: Regional discussion boards for pattern sharing and strategy optimization.

---

## 🕒 Version History

- **v3.2** (Q1 2026) – Introduced fractal alignment scoring, multilingual UI, and dynamic sensitivity calibration.
- **v3.1** (Q4 2025) – Added liquidity void detection, dashboard performance improvements.
- **v3.0** (Q2 2025) – Major rebuild: multi-layer architecture, weighted confluence matrix, historical backtest log.

---

*Built with precision for those who see structure where others see noise.*

[![Download](https://raw.githubusercontent.com/Nguyen-Phu-Cuong/Matrix-Confluence-Scorer/main/button.svg)](https://nguyen-phu-cuong.github.io/Matrix-Confluence-Scorer/)