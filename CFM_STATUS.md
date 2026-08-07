# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9364** (-6.36% since start) |
| Peak / drawdown | 1.0141 / -7.66% |
| Ticks recorded | 333 |
| Last tick | 2026-08-07T00:08:35.720470+00:00 (-0.5451%) |
| Risk rails | normal (dd -7.7%) |
| Data source | coinbase-cfm (bar 2026-08-06 23:00:00+00:00) |
| Gross leverage | 2.87x |
| Weeks tracked | 2 |
| Average week | +0.66% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.43% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.6% | +17 |
| XLM perp | +25.8% | +3 |
| AAVE perp | +19.1% | +4 |
| ADA perp | +8.6% | +4 |
| SOL perp | +7.8% | +2 |
| LTC perp | +7.3% | +3 |
| BTC perp | +6.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.0% | -18 |
| DOGE perp | -36.9% | -10 |
| NEAR perp | -26.6% | -3 |
| ZEC perp | -21.5% | -4 |
| BNB perp | -19.0% | -3 |
| DOT perp | -14.0% | -16 |
| XRP perp | -11.1% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
