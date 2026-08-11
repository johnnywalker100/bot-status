# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9139** (-8.61% since start) |
| Peak / drawdown | 1.0141 / -9.88% |
| Ticks recorded | 451 |
| Last tick | 2026-08-11T23:08:45.206520+00:00 (+0.0672%) |
| Risk rails | normal (dd -9.9%) |
| Data source | coinbase-cfm (bar 2026-08-11 22:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.37% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.60% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.9% | +16 |
| AAVE perp | +24.1% | +5 |
| XLM perp | +17.7% | +2 |
| LTC perp | +17.4% | +7 |
| BTC perp | +13.9% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -40.3% | -6 |
| DOGE perp | -39.4% | -10 |
| BCH perp | -37.4% | -16 |
| ZEC perp | -26.2% | -5 |
| NEAR perp | -17.5% | -2 |
| ADA perp | -16.3% | -8 |
| DOT perp | -6.9% | -8 |
| LINK perp | -4.8% | -1 |
| SOL perp | -4.2% | -1 |
| AVAX perp | -0.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
