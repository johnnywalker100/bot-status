# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9610** (-3.90% since start) |
| Peak / drawdown | 1.0141 / -5.23% |
| Ticks recorded | 136 |
| Last tick | 2026-07-29T18:09:02.514912+00:00 (-0.9802%) |
| Risk rails | normal (dd -5.2%) |
| Data source | coinbase-cfm (bar 2026-07-29 17:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +3.97% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.97% / +3.97% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.9% | +4 |
| ADA perp | +19.1% | +11 |
| XLM perp | +18.1% | +2 |
| BCH perp | +13.2% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +8.8% | +11 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.9% | -13 |
| LTC perp | -37.9% | -16 |
| BNB perp | -29.7% | -5 |
| NEAR perp | -25.2% | -3 |
| BTC perp | -20.1% | -3 |
| LINK perp | -17.4% | -4 |
| ZEC perp | -14.7% | -3 |
| AVAX perp | -8.8% | -13 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
