# Research artefacts

All charts derived from public ETH hourly OHLC + Hyperliquid funding history
over 2024-05-14 → 2026-05-14 (2 years, 17 520 hourly bars).

## Session-timing backtest

| chart | what it shows |
|---|---|
| `backtest_session_sweep.png` | 24×24 grid of `enter_hour × exit_hour` ETH-PERP long, daily, $10 starting capital, fixed-percentage stop-loss. |
| `backtest_session_timing.png` | Equity curves of top combinations vs buy-and-hold benchmark. |
| `research_persistence_rolling.png` | 90-day rolling Sharpe across full 2-year history; majority of windows profitable. |
| `research_persistence_regimes.png` | Same grid split by bull / flat / bear regime (90-day rolling ETH return ±5%). Pattern is structural across regimes. |
| `research_persistence_robust.png` | % of 90-day rolling windows profitable per (entry, exit) pair. |
| `research_funding_by_hour.png` | Hyperliquid funding rate by UTC hour. No hour-of-day seasonality. |
