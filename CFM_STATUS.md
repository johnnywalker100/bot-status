# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9571** (-4.29% since start) |
| Peak / drawdown | 1.0141 / -5.62% |
| Ticks recorded | 42 |
| Last tick | 2026-07-25T21:08:49.658035+00:00 (+0.7633%) |
| Risk rails | normal (dd -5.6%) |
| Data source | coinbase-cfm (bar 2026-07-25 20:00:00+00:00) |
| Gross leverage | 2.63x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.7% | +5 |
| ETH perp | +17.6% | +9 |
| BCH perp | +13.1% | +6 |
| ADA perp | +12.0% | +7 |
| ONDO perp | +4.0% | +1 |
| SOL perp | +3.9% | +1 |
| HBAR perp | +3.7% | +1 |
| AVAX perp | +0.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.0% | -9 |
| LTC perp | -24.0% | -10 |
| ZEC perp | -20.1% | -4 |
| NEAR perp | -18.7% | -2 |
| SUI perp | -18.6% | -5 |
| PEPE perp | -17.3% | -6 |
| LINK perp | -13.1% | -3 |
| HYPE perp | -12.1% | -2 |
| ENA perp | -9.0% | -2 |
| BTC perp | -6.7% | -1 |
| SHIB perp | -5.6% | -11 |
| DOT perp | -5.1% | -6 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
