# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8792** (-12.08% since start) |
| Peak / drawdown | 1.0141 / -13.31% |
| Ticks recorded | 886 |
| Last tick | 2026-08-30T05:08:10.195041+00:00 (+0.0074%) |
| Risk rails | brake: drawdown -13.3% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-30 04:00:00+00:00) |
| Gross leverage | 0.07x |
| Weeks tracked | 5 |
| Average week | -0.99% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.90% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +2.8% | +1 |
| AVAX perp | +2.5% | +3 |
| DOT perp | +1.9% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
