# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9189** (-8.11% since start) |
| Peak / drawdown | 1.0141 / -9.39% |
| Ticks recorded | 461 |
| Last tick | 2026-08-12T09:09:47.732156+00:00 (+0.1316%) |
| Risk rails | normal (dd -9.4%) |
| Data source | coinbase-cfm (bar 2026-08-12 08:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.9% | +16 |
| AAVE perp | +24.2% | +5 |
| LTC perp | +19.7% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.8% | -18 |
| DOGE perp | -38.9% | -10 |
| BTC perp | -34.7% | -5 |
| DOT perp | -20.5% | -24 |
| ADA perp | -20.2% | -10 |
| BNB perp | -20.0% | -3 |
| ZEC perp | -15.6% | -3 |
| LINK perp | -14.3% | -3 |
| NEAR perp | -8.9% | -1 |
| XLM perp | -8.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
