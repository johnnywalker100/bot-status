# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9526** (-4.74% since start) |
| Peak / drawdown | 1.0141 / -6.07% |
| Ticks recorded | 47 |
| Last tick | 2026-07-26T02:08:43.642624+00:00 (-0.4997%) |
| Risk rails | normal (dd -6.1%) |
| Data source | coinbase-cfm (bar 2026-07-26 01:00:00+00:00) |
| Gross leverage | 3.07x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.3% | +4 |
| ADA perp | +19.0% | +11 |
| AVAX perp | +16.3% | +23 |
| ETH perp | +11.8% | +6 |
| BCH perp | +11.0% | +5 |
| XLM perp | +9.3% | +1 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.0% | -9 |
| LTC perp | -26.9% | -11 |
| ONDO perp | -20.0% | -5 |
| NEAR perp | -18.8% | -2 |
| PEPE perp | -17.4% | -6 |
| ZEC perp | -15.3% | -3 |
| SUI perp | -14.9% | -4 |
| BTC perp | -13.5% | -2 |
| LINK perp | -13.2% | -3 |
| HYPE perp | -12.2% | -2 |
| ENA perp | -9.0% | -2 |
| BNB perp | -6.0% | -1 |
| XRP perp | -5.8% | -1 |
| HBAR perp | -3.7% | -1 |
| SHIB perp | -2.7% | -5 |
| DOT perp | -2.6% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
