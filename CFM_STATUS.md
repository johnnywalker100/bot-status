# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9311** (-6.89% since start) |
| Peak / drawdown | 1.0141 / -8.18% |
| Ticks recorded | 1594 |
| Last tick | 2026-09-28T22:08:24.032205+00:00 (-0.5852%) |
| Risk rails | normal (dd -8.2%) |
| Data source | coinbase-cfm (bar 2026-09-28 21:00:00+00:00) |
| Gross leverage | 0.87x |
| Weeks tracked | 10 |
| Average week | +0.12% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -3.47% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.7% | +1 |
| ETH perp | +11.5% | +4 |
| DOT perp | +11.2% | +9 |
| BTC perp | +8.9% | +1 |
| AAVE perp | +7.8% | +1 |
| AVAX perp | +7.8% | +7 |
| BCH perp | +6.6% | +2 |
| SOL perp | +6.3% | +1 |
| LTC perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |
| ADA perp | -2.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
