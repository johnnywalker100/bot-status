# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9928** (-0.72% since start) |
| Peak / drawdown | 1.0141 / -2.10% |
| Ticks recorded | 27 |
| Last tick | 2026-07-25T03:08:51.149645+00:00 (-0.2171%) |
| Risk rails | normal (dd -1.9%) |
| Data source | coinbase-cfm (bar 2026-07-25 02:00:00+00:00) |
| Gross leverage | 2.67x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.9% | +5 |
| ETH perp | +16.8% | +9 |
| BCH perp | +12.7% | +6 |
| ADA perp | +11.5% | +7 |
| HBAR perp | +7.1% | +2 |
| ONDO perp | +3.8% | +1 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -31.5% | -9 |
| LTC perp | -23.2% | -10 |
| ZEC perp | -19.6% | -4 |
| PEPE perp | -19.1% | -7 |
| NEAR perp | -18.2% | -2 |
| SUI perp | -17.9% | -5 |
| SHIB perp | -14.8% | -35 |
| LINK perp | -12.6% | -3 |
| HYPE perp | -11.5% | -2 |
| ENA perp | -8.8% | -2 |
| BTC perp | -6.4% | -1 |
| DOT perp | -4.1% | -5 |
| AVAX perp | -0.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
