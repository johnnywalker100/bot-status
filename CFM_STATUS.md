# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9679** (-3.21% since start) |
| Peak / drawdown | 1.0141 / -4.56% |
| Ticks recorded | 1539 |
| Last tick | 2026-09-26T15:08:11.903033+00:00 (+0.6491%) |
| Risk rails | normal (dd -4.6%) |
| Data source | coinbase-cfm (bar 2026-09-26 14:00:00+00:00) |
| Gross leverage | 0.87x |
| Weeks tracked | 9 |
| Average week | +0.56% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.0% | +1 |
| DOT perp | +11.7% | +9 |
| ETH perp | +11.1% | +4 |
| AVAX perp | +8.0% | +7 |
| AAVE perp | +8.0% | +1 |
| LINK perp | +7.4% | +1 |
| BCH perp | +6.9% | +2 |
| SOL perp | +6.3% | +1 |
| LTC perp | +3.8% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
