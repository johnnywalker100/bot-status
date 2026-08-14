# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9271** (-7.29% since start) |
| Peak / drawdown | 1.0141 / -8.58% |
| Ticks recorded | 522 |
| Last tick | 2026-08-14T23:10:20.083996+00:00 (-0.2907%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-08-14 22:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 3 |
| Average week | +0.11% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.3% | +3 |
| AAVE perp | +23.0% | +5 |
| ETH perp | +10.1% | +5 |
| AVAX perp | +9.7% | +14 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -33.8% | -9 |
| BTC perp | -33.8% | -5 |
| BNB perp | -32.7% | -5 |
| NEAR perp | -26.2% | -3 |
| LINK perp | -24.2% | -5 |
| BCH perp | -22.0% | -10 |
| ADA perp | -17.4% | -9 |
| ZEC perp | -15.8% | -3 |
| LTC perp | -14.1% | -6 |
| DOT perp | -8.2% | -10 |
| XRP perp | -5.3% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
