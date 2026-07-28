# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9565** (-4.35% since start) |
| Peak / drawdown | 1.0141 / -5.68% |
| Ticks recorded | 107 |
| Last tick | 2026-07-28T14:08:49.491699+00:00 (+1.0143%) |
| Risk rails | normal (dd -5.7%) |
| Data source | coinbase-cfm (bar 2026-07-28 13:00:00+00:00) |
| Gross leverage | 2.97x |
| Weeks tracked | 1 |
| Average week | +3.48% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.48% / +3.48% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +30.7% | +6 |
| ADA perp | +22.9% | +14 |
| BCH perp | +13.2% | +6 |
| ETH perp | +9.8% | +5 |
| DOT perp | +6.3% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.0% | -14 |
| LTC perp | -33.7% | -14 |
| LINK perp | -25.9% | -6 |
| BNB perp | -23.7% | -4 |
| BTC perp | -19.8% | -3 |
| NEAR perp | -17.1% | -2 |
| ZEC perp | -14.5% | -3 |
| AVAX perp | -14.1% | -21 |
| XLM perp | -8.9% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
