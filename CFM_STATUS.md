# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9717** (-2.83% since start) |
| Peak / drawdown | 1.0141 / -4.18% |
| Ticks recorded | 1541 |
| Last tick | 2026-09-26T17:08:20.622905+00:00 (+0.2056%) |
| Risk rails | normal (dd -4.2%) |
| Data source | coinbase-cfm (bar 2026-09-26 16:00:00+00:00) |
| Gross leverage | 0.87x |
| Weeks tracked | 9 |
| Average week | +0.60% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.1% | +1 |
| DOT perp | +12.0% | +9 |
| ETH perp | +11.1% | +4 |
| AAVE perp | +8.0% | +1 |
| AVAX perp | +7.9% | +7 |
| LINK perp | +7.4% | +1 |
| BCH perp | +6.9% | +2 |
| SOL perp | +6.2% | +1 |
| LTC perp | +3.7% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
