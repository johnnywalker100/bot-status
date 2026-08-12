# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9222** (-7.78% since start) |
| Peak / drawdown | 1.0141 / -9.07% |
| Ticks recorded | 473 |
| Last tick | 2026-08-12T21:09:21.416848+00:00 (+0.3459%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-08-12 20:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.07% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.7% | +16 |
| AAVE perp | +24.0% | +5 |
| LTC perp | +21.9% | +9 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.6% | -18 |
| DOGE perp | -38.2% | -10 |
| BTC perp | -34.4% | -5 |
| DOT perp | -20.3% | -24 |
| BNB perp | -19.9% | -3 |
| ADA perp | -19.8% | -10 |
| ZEC perp | -16.0% | -3 |
| LINK perp | -14.2% | -3 |
| NEAR perp | -8.8% | -1 |
| XLM perp | -8.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
