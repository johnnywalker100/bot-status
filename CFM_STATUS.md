# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9630** (-3.70% since start) |
| Peak / drawdown | 1.0141 / -5.04% |
| Ticks recorded | 122 |
| Last tick | 2026-07-29T05:08:39.979554+00:00 (-0.8581%) |
| Risk rails | normal (dd -5.0%) |
| Data source | coinbase-cfm (bar 2026-07-29 04:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +4.19% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.19% / +4.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.4% | +4 |
| ADA perp | +18.6% | +11 |
| XLM perp | +18.0% | +2 |
| BCH perp | +13.2% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +9.5% | +12 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.6% | -13 |
| LTC perp | -37.4% | -16 |
| BNB perp | -29.5% | -5 |
| NEAR perp | -25.3% | -3 |
| BTC perp | -19.9% | -3 |
| LINK perp | -17.4% | -4 |
| ZEC perp | -14.4% | -3 |
| AVAX perp | -8.6% | -13 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
