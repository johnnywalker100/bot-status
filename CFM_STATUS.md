# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9312** (-6.88% since start) |
| Peak / drawdown | 1.0141 / -8.17% |
| Ticks recorded | 362 |
| Last tick | 2026-08-08T06:08:39.113873+00:00 (+0.1650%) |
| Risk rails | normal (dd -8.2%) |
| Data source | coinbase-cfm (bar 2026-08-08 05:00:00+00:00) |
| Gross leverage | 2.61x |
| Weeks tracked | 2 |
| Average week | +0.38% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.98% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.9% | +15 |
| AAVE perp | +24.3% | +5 |
| ADA perp | +12.9% | +6 |
| XLM perp | +8.7% | +1 |
| SOL perp | +8.0% | +2 |
| LTC perp | +7.3% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.2% | -12 |
| BNB perp | -38.2% | -6 |
| BCH perp | -32.5% | -14 |
| ZEC perp | -16.3% | -3 |
| DOT perp | -14.0% | -16 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.6% | -1 |
| AVAX perp | -5.6% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
