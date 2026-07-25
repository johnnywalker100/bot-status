# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0026** (+0.26% since start) |
| Peak / drawdown | 1.0141 / -1.13% |
| Ticks recorded | 36 |
| Last tick | 2026-07-25T12:08:42.048463+00:00 (-0.0357%) |
| Risk rails | normal (dd -1.1%) |
| Data source | coinbase-cfm (bar 2026-07-25 11:00:00+00:00) |
| Gross leverage | 2.73x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.1% | +6 |
| ETH perp | +18.5% | +10 |
| BCH perp | +12.6% | +6 |
| ADA perp | +11.3% | +7 |
| HBAR perp | +7.0% | +2 |
| ONDO perp | +3.8% | +1 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.6% | -10 |
| LTC perp | -22.9% | -10 |
| ZEC perp | -19.1% | -4 |
| PEPE perp | -18.7% | -7 |
| NEAR perp | -17.8% | -2 |
| SUI perp | -17.6% | -5 |
| SHIB perp | -14.8% | -35 |
| LINK perp | -12.4% | -3 |
| HYPE perp | -11.5% | -2 |
| ENA perp | -8.6% | -2 |
| BTC perp | -6.4% | -1 |
| DOT perp | -4.1% | -5 |
| AVAX perp | -0.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
