# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9288** (-7.12% since start) |
| Peak / drawdown | 1.0141 / -8.42% |
| Ticks recorded | 506 |
| Last tick | 2026-08-14T06:08:37.198735+00:00 (-0.1859%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-08-14 05:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | +0.17% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.7% | +3 |
| AAVE perp | +23.6% | +5 |
| ETH perp | +10.1% | +5 |
| AVAX perp | +9.7% | +14 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -34.1% | -5 |
| DOGE perp | -33.9% | -9 |
| BNB perp | -32.8% | -5 |
| NEAR perp | -26.1% | -3 |
| LINK perp | -23.6% | -5 |
| BCH perp | -22.3% | -10 |
| ADA perp | -17.7% | -9 |
| LTC perp | -12.0% | -5 |
| ZEC perp | -10.6% | -2 |
| DOT perp | -8.2% | -10 |
| XRP perp | -5.4% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
