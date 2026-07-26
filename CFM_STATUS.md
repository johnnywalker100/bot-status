# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9574** (-4.26% since start) |
| Peak / drawdown | 1.0141 / -5.60% |
| Ticks recorded | 46 |
| Last tick | 2026-07-26T01:08:43.909950+00:00 (-0.1648%) |
| Risk rails | normal (dd -5.5%) |
| Data source | coinbase-cfm (bar 2026-07-26 00:00:00+00:00) |
| Gross leverage | 3.05x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.2% | +4 |
| ADA perp | +18.9% | +11 |
| AVAX perp | +16.2% | +23 |
| ETH perp | +11.7% | +6 |
| BCH perp | +10.9% | +5 |
| XLM perp | +9.3% | +1 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -33.6% | -9 |
| LTC perp | -26.7% | -11 |
| ONDO perp | -20.0% | -5 |
| NEAR perp | -18.7% | -2 |
| PEPE perp | -17.2% | -6 |
| ZEC perp | -15.2% | -3 |
| SUI perp | -14.9% | -4 |
| BTC perp | -13.4% | -2 |
| LINK perp | -13.1% | -3 |
| HYPE perp | -12.1% | -2 |
| ENA perp | -9.0% | -2 |
| BNB perp | -5.9% | -1 |
| XRP perp | -5.7% | -1 |
| HBAR perp | -3.7% | -1 |
| SHIB perp | -3.1% | -6 |
| DOT perp | -2.6% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
