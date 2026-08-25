# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8822** (-11.78% since start) |
| Peak / drawdown | 1.0141 / -13.01% |
| Ticks recorded | 775 |
| Last tick | 2026-08-25T13:08:25.500376+00:00 (+0.1411%) |
| Risk rails | brake: drawdown -13.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-25 12:00:00+00:00) |
| Gross leverage | 0.27x |
| Weeks tracked | 5 |
| Average week | -0.92% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.56% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.3% | +1 |
| SOL perp | +5.6% | +1 |
| BCH perp | +3.0% | +1 |
| DOT perp | +3.0% | +3 |
| ETH perp | +2.8% | +1 |
| AVAX perp | +2.6% | +3 |
| ADA perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
