# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9210** (-7.90% since start) |
| Peak / drawdown | 1.0141 / -9.18% |
| Ticks recorded | 373 |
| Last tick | 2026-08-08T17:09:13.051193+00:00 (+0.0305%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-08-08 16:00:00+00:00) |
| Gross leverage | 2.65x |
| Weeks tracked | 2 |
| Average week | -0.16% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.07% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.2% | +14 |
| AAVE perp | +24.8% | +5 |
| ADA perp | +13.0% | +6 |
| XLM perp | +9.0% | +1 |
| SOL perp | +8.3% | +2 |
| LTC perp | +7.5% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.3% | -12 |
| BNB perp | -39.4% | -6 |
| BCH perp | -33.0% | -14 |
| ZEC perp | -16.5% | -3 |
| DOT perp | -14.2% | -16 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -5.7% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
