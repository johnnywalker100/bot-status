# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8845** (-11.55% since start) |
| Peak / drawdown | 1.0141 / -12.78% |
| Ticks recorded | 771 |
| Last tick | 2026-08-25T09:08:21.208198+00:00 (+0.0174%) |
| Risk rails | brake: drawdown -12.8% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-25 08:00:00+00:00) |
| Gross leverage | 0.27x |
| Weeks tracked | 5 |
| Average week | -0.87% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.31% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.3% | +1 |
| SOL perp | +5.7% | +1 |
| DOT perp | +3.1% | +3 |
| BCH perp | +3.1% | +1 |
| ETH perp | +2.8% | +1 |
| AVAX perp | +2.6% | +3 |
| ADA perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
