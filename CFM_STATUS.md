# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9175** (-8.25% since start) |
| Peak / drawdown | 1.0141 / -9.53% |
| Ticks recorded | 480 |
| Last tick | 2026-08-13T04:08:19.448566+00:00 (+0.0163%) |
| Risk rails | normal (dd -9.5%) |
| Data source | coinbase-cfm (bar 2026-08-13 03:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 3 |
| Average week | -0.24% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.8% | +14 |
| AAVE perp | +24.0% | +5 |
| LTC perp | +22.0% | +9 |
| SOL perp | +12.5% | +3 |
| XLM perp | +8.8% | +1 |
| AVAX perp | +7.8% | +11 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.4% | -9 |
| BCH perp | -32.8% | -14 |
| BTC perp | -20.8% | -3 |
| BNB perp | -20.0% | -3 |
| LINK perp | -19.0% | -4 |
| NEAR perp | -18.0% | -2 |
| DOT perp | -16.9% | -20 |
| ADA perp | -16.0% | -8 |
| XRP perp | -11.0% | -2 |
| ZEC perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
