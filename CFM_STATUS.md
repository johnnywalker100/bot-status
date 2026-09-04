# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8812** (-11.88% since start) |
| Peak / drawdown | 1.0141 / -13.10% |
| Ticks recorded | 1010 |
| Last tick | 2026-09-04T09:08:11.847096+00:00 (+0.0645%) |
| Risk rails | brake: drawdown -13.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-04 08:00:00+00:00) |
| Gross leverage | 0.09x |
| Weeks tracked | 6 |
| Average week | -0.78% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +5.9% | +1 |
| AVAX perp | +2.6% | +3 |
| DOT perp | +1.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
