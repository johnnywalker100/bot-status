# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9943** (-0.57% since start) |
| Peak / drawdown | 1.0141 / -1.95% |
| Ticks recorded | 28 |
| Last tick | 2026-07-25T04:08:40.263309+00:00 (+0.1572%) |
| Risk rails | normal (dd -2.1%) |
| Data source | coinbase-cfm (bar 2026-07-25 03:00:00+00:00) |
| Gross leverage | 2.67x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.0% | +5 |
| ETH perp | +16.9% | +9 |
| BCH perp | +12.7% | +6 |
| ADA perp | +11.6% | +7 |
| HBAR perp | +7.1% | +2 |
| ONDO perp | +3.8% | +1 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -31.6% | -9 |
| LTC perp | -23.3% | -10 |
| ZEC perp | -19.6% | -4 |
| PEPE perp | -19.1% | -7 |
| NEAR perp | -18.2% | -2 |
| SUI perp | -17.9% | -5 |
| SHIB perp | -14.9% | -35 |
| LINK perp | -12.6% | -3 |
| HYPE perp | -11.5% | -2 |
| ENA perp | -8.8% | -2 |
| BTC perp | -6.5% | -1 |
| DOT perp | -4.1% | -5 |
| AVAX perp | -0.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
