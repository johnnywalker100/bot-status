# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8785** (-12.15% since start) |
| Peak / drawdown | 1.0141 / -13.37% |
| Ticks recorded | 797 |
| Last tick | 2026-08-26T11:08:31.816986+00:00 (+0.3477%) |
| Risk rails | brake: drawdown -13.4% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-26 10:00:00+00:00) |
| Gross leverage | 0.26x |
| Weeks tracked | 5 |
| Average week | -1.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.96% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.2% | +1 |
| SOL perp | +5.5% | +1 |
| BCH perp | +3.0% | +1 |
| DOT perp | +2.9% | +3 |
| ETH perp | +2.8% | +1 |
| AVAX perp | +2.5% | +3 |
| ADA perp | +2.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
