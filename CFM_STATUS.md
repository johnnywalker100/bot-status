# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9438** (-5.62% since start) |
| Peak / drawdown | 1.0141 / -6.93% |
| Ticks recorded | 1442 |
| Last tick | 2026-09-22T13:08:21.687821+00:00 (+1.1870%) |
| Risk rails | normal (dd -6.9%) |
| Data source | coinbase-cfm (bar 2026-09-22 12:00:00+00:00) |
| Gross leverage | 0.90x |
| Weeks tracked | 9 |
| Average week | +0.27% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.1% | +1 |
| SOL perp | +12.5% | +2 |
| XLM perp | +11.3% | +1 |
| DOT perp | +11.2% | +9 |
| AAVE perp | +7.7% | +1 |
| AVAX perp | +7.0% | +6 |
| LINK perp | +6.9% | +1 |
| ETH perp | +5.9% | +2 |
| LTC perp | +3.3% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
