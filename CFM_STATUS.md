# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9297** (-7.03% since start) |
| Peak / drawdown | 1.0141 / -8.32% |
| Ticks recorded | 379 |
| Last tick | 2026-08-08T23:08:31.279449+00:00 (+0.4529%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-08-08 22:00:00+00:00) |
| Gross leverage | 2.75x |
| Weeks tracked | 2 |
| Average week | +0.30% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.14% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.9% | +15 |
| AAVE perp | +24.5% | +5 |
| ADA perp | +12.8% | +6 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.2% | +2 |
| LTC perp | +7.4% | +3 |
| XRP perp | +5.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.2% | -13 |
| BNB perp | -38.7% | -6 |
| BCH perp | -34.8% | -15 |
| ZEC perp | -16.3% | -3 |
| DOT perp | -14.0% | -16 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -6.3% | -9 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
