# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9209** (-7.91% since start) |
| Peak / drawdown | 1.0141 / -9.19% |
| Ticks recorded | 523 |
| Last tick | 2026-08-15T00:11:56.503597+00:00 (-0.6692%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-08-14 23:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 3 |
| Average week | -0.12% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.7% | +3 |
| AAVE perp | +23.4% | +5 |
| ETH perp | +10.2% | +5 |
| AVAX perp | +9.9% | +14 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.2% | -9 |
| BNB perp | -33.0% | -5 |
| BTC perp | -27.3% | -4 |
| NEAR perp | -26.8% | -3 |
| LINK perp | -24.4% | -5 |
| BCH perp | -22.3% | -10 |
| ADA perp | -17.6% | -9 |
| LTC perp | -14.2% | -6 |
| ZEC perp | -10.7% | -2 |
| DOT perp | -8.3% | -10 |
| XRP perp | -5.4% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
