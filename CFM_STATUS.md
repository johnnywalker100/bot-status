# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8777** (-12.23% since start) |
| Peak / drawdown | 1.0141 / -13.45% |
| Ticks recorded | 952 |
| Last tick | 2026-09-01T23:08:14.541449+00:00 (+0.0045%) |
| Risk rails | brake: drawdown -13.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-01 22:00:00+00:00) |
| Gross leverage | 0.14x |
| Weeks tracked | 6 |
| Average week | -0.85% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +5.7% | +1 |
| ETH perp | +2.8% | +1 |
| DOT perp | +2.0% | +2 |
| AVAX perp | +1.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| ADA perp | -2.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
