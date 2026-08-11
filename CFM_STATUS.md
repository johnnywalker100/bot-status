# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9133** (-8.67% since start) |
| Peak / drawdown | 1.0141 / -9.94% |
| Ticks recorded | 450 |
| Last tick | 2026-08-11T22:10:17.252718+00:00 (-0.9115%) |
| Risk rails | normal (dd -9.9%) |
| Data source | coinbase-cfm (bar 2026-08-11 21:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.39% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.67% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.0% | +16 |
| AAVE perp | +24.1% | +5 |
| XLM perp | +17.8% | +2 |
| LTC perp | +17.4% | +7 |
| BTC perp | +13.9% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -40.2% | -6 |
| DOGE perp | -39.7% | -10 |
| BCH perp | -37.4% | -16 |
| ZEC perp | -26.4% | -5 |
| NEAR perp | -17.5% | -2 |
| ADA perp | -16.3% | -8 |
| DOT perp | -6.0% | -7 |
| LINK perp | -4.8% | -1 |
| SOL perp | -4.2% | -1 |
| AVAX perp | -0.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
