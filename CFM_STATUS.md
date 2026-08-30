# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8800** (-12.00% since start) |
| Peak / drawdown | 1.0141 / -13.22% |
| Ticks recorded | 896 |
| Last tick | 2026-08-30T15:08:12.689215+00:00 (-0.0176%) |
| Risk rails | brake: drawdown -13.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-30 14:00:00+00:00) |
| Gross leverage | 0.07x |
| Weeks tracked | 5 |
| Average week | -0.97% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.80% |

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
