# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9217** (-7.83% since start) |
| Peak / drawdown | 1.0141 / -9.12% |
| Ticks recorded | 449 |
| Last tick | 2026-08-11T21:08:36.068079+00:00 (-0.6387%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-08-11 20:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.09% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.6% | +16 |
| AAVE perp | +23.9% | +5 |
| XLM perp | +17.6% | +2 |
| LTC perp | +17.2% | +7 |
| BTC perp | +13.8% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -39.9% | -6 |
| DOGE perp | -38.8% | -10 |
| BCH perp | -37.0% | -16 |
| ZEC perp | -31.2% | -6 |
| NEAR perp | -17.2% | -2 |
| ADA perp | -16.1% | -8 |
| DOT perp | -6.0% | -7 |
| LINK perp | -4.7% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
