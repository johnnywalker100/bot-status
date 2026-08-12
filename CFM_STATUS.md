# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9190** (-8.10% since start) |
| Peak / drawdown | 1.0141 / -9.38% |
| Ticks recorded | 472 |
| Last tick | 2026-08-12T20:08:27.950907+00:00 (-0.1690%) |
| Risk rails | normal (dd -9.4%) |
| Data source | coinbase-cfm (bar 2026-08-12 19:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.7% | +16 |
| AAVE perp | +24.1% | +5 |
| LTC perp | +19.5% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.8% | -18 |
| DOGE perp | -38.4% | -10 |
| BTC perp | -34.5% | -5 |
| DOT perp | -20.4% | -24 |
| BNB perp | -19.9% | -3 |
| ADA perp | -19.9% | -10 |
| ZEC perp | -16.0% | -3 |
| LINK perp | -14.3% | -3 |
| NEAR perp | -8.9% | -1 |
| XLM perp | -8.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
