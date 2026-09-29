# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9616** (-3.84% since start) |
| Peak / drawdown | 1.0141 / -5.18% |
| Ticks recorded | 1608 |
| Last tick | 2026-09-29T12:08:32.194095+00:00 (+0.8761%) |
| Risk rails | normal (dd -5.2%) |
| Data source | coinbase-cfm (bar 2026-09-29 11:00:00+00:00) |
| Gross leverage | 0.86x |
| Weeks tracked | 10 |
| Average week | +0.43% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.0% | +1 |
| DOT perp | +11.4% | +9 |
| ETH perp | +11.4% | +4 |
| AAVE perp | +8.9% | +1 |
| BTC perp | +8.8% | +1 |
| BCH perp | +6.5% | +2 |
| SOL perp | +6.2% | +1 |
| AVAX perp | +6.2% | +5 |
| LTC perp | +3.6% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
