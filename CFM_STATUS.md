# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8872** (-11.28% since start) |
| Peak / drawdown | 1.0141 / -12.52% |
| Ticks recorded | 722 |
| Last tick | 2026-08-23T08:08:51.164740+00:00 (+0.0509%) |
| Risk rails | brake: drawdown -12.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-23 07:00:00+00:00) |
| Gross leverage | 0.25x |
| Weeks tracked | 4 |
| Average week | -1.01% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.07% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +6.9% | +1 |
| SOL perp | +5.2% | +1 |
| DOT perp | +3.0% | +3 |
| BCH perp | +3.0% | +1 |
| ETH perp | +2.7% | +1 |
| ADA perp | +2.5% | +1 |
| AVAX perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
