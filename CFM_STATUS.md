# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9417** (-5.83% since start) |
| Peak / drawdown | 1.0141 / -7.14% |
| Ticks recorded | 519 |
| Last tick | 2026-08-14T19:11:56.886420+00:00 (-0.1189%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-08-14 18:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 3 |
| Average week | +0.63% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.3% | +3 |
| AAVE perp | +22.8% | +5 |
| AVAX perp | +10.2% | +15 |
| ETH perp | +9.9% | +5 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -33.3% | -5 |
| DOGE perp | -33.3% | -9 |
| BNB perp | -32.2% | -5 |
| NEAR perp | -25.3% | -3 |
| LINK perp | -23.8% | -5 |
| BCH perp | -21.5% | -10 |
| ADA perp | -19.0% | -10 |
| ZEC perp | -15.5% | -3 |
| LTC perp | -13.9% | -6 |
| DOT perp | -8.0% | -10 |
| XRP perp | -5.3% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
