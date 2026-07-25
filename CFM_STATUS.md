# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0098** (+0.98% since start) |
| Peak / drawdown | 1.0141 / -0.42% |
| Ticks recorded | 32 |
| Last tick | 2026-07-25T08:08:45.974729+00:00 (+0.4938%) |
| Risk rails | normal (dd -0.9%) |
| Data source | coinbase-cfm (bar 2026-07-25 07:00:00+00:00) |
| Gross leverage | 2.65x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.5% | +5 |
| ETH perp | +16.6% | +9 |
| BCH perp | +12.6% | +6 |
| ADA perp | +11.2% | +7 |
| HBAR perp | +7.0% | +2 |
| ONDO perp | +3.7% | +1 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.4% | -10 |
| LTC perp | -22.9% | -10 |
| ZEC perp | -18.8% | -4 |
| PEPE perp | -18.5% | -7 |
| NEAR perp | -17.7% | -2 |
| SUI perp | -17.5% | -5 |
| SHIB perp | -15.0% | -36 |
| LINK perp | -12.3% | -3 |
| HYPE perp | -11.3% | -2 |
| ENA perp | -8.7% | -2 |
| BTC perp | -6.4% | -1 |
| DOT perp | -4.0% | -5 |
| AVAX perp | -0.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
