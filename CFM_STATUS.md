# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0049** (+0.49% since start) |
| Peak / drawdown | 1.0141 / -0.91% |
| Ticks recorded | 31 |
| Last tick | 2026-07-25T07:08:41.387106+00:00 (+0.1959%) |
| Risk rails | normal (dd -1.1%) |
| Data source | coinbase-cfm (bar 2026-07-25 06:00:00+00:00) |
| Gross leverage | 2.64x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.7% | +5 |
| ETH perp | +16.7% | +9 |
| BCH perp | +12.7% | +6 |
| ADA perp | +11.3% | +7 |
| HBAR perp | +7.0% | +2 |
| ONDO perp | +3.8% | +1 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -31.1% | -9 |
| LTC perp | -23.0% | -10 |
| ZEC perp | -19.0% | -4 |
| PEPE perp | -18.7% | -7 |
| NEAR perp | -17.9% | -2 |
| SUI perp | -17.6% | -5 |
| SHIB perp | -15.1% | -36 |
| LINK perp | -12.4% | -3 |
| HYPE perp | -11.4% | -2 |
| ENA perp | -8.7% | -2 |
| BTC perp | -6.4% | -1 |
| DOT perp | -4.1% | -5 |
| AVAX perp | -0.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
