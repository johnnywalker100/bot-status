# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8799** (-12.01% since start) |
| Peak / drawdown | 1.0141 / -13.24% |
| Ticks recorded | 1030 |
| Last tick | 2026-09-05T06:08:26.846605+00:00 (+0.0487%) |
| Risk rails | brake: drawdown -13.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-05 05:00:00+00:00) |
| Gross leverage | 0.30x |
| Weeks tracked | 6 |
| Average week | -0.81% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.4% | +1 |
| SOL perp | +5.8% | +1 |
| DOGE perp | +4.8% | +1 |
| AVAX perp | +4.2% | +5 |
| LTC perp | +3.0% | +1 |
| ETH perp | +2.8% | +1 |
| DOT perp | +2.1% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
