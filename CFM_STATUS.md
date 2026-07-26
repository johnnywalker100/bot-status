# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9589** (-4.11% since start) |
| Peak / drawdown | 1.0141 / -5.44% |
| Ticks recorded | 45 |
| Last tick | 2026-07-26T00:08:55.203554+00:00 (+0.0215%) |
| Risk rails | normal (dd -5.4%) |
| Data source | coinbase-cfm (bar 2026-07-25 23:00:00+00:00) |
| Gross leverage | 2.67x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +24.0% | +5 |
| ETH perp | +17.6% | +9 |
| BCH perp | +13.1% | +6 |
| ADA perp | +10.3% | +6 |
| ONDO perp | +4.0% | +1 |
| SOL perp | +3.9% | +1 |
| HBAR perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -33.7% | -9 |
| LTC perp | -24.3% | -10 |
| ZEC perp | -20.3% | -4 |
| NEAR perp | -18.7% | -2 |
| SUI perp | -18.6% | -5 |
| PEPE perp | -17.1% | -6 |
| LINK perp | -13.1% | -3 |
| HYPE perp | -12.1% | -2 |
| ENA perp | -9.0% | -2 |
| BTC perp | -6.7% | -1 |
| BNB perp | -5.9% | -1 |
| SHIB perp | -5.6% | -11 |
| DOT perp | -5.1% | -6 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
