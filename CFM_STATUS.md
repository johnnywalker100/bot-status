# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8772** (-12.28% since start) |
| Peak / drawdown | 1.0141 / -13.50% |
| Ticks recorded | 972 |
| Last tick | 2026-09-02T19:08:17.998288+00:00 (+0.0339%) |
| Risk rails | brake: drawdown -13.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-02 18:00:00+00:00) |
| Gross leverage | 0.14x |
| Weeks tracked | 6 |
| Average week | -0.86% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +5.7% | +1 |
| ETH perp | +2.7% | +1 |
| DOT perp | +2.0% | +2 |
| AVAX perp | +1.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| ADA perp | -2.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
