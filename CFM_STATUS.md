# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9569** (-4.31% since start) |
| Peak / drawdown | 1.0141 / -5.64% |
| Ticks recorded | 38 |
| Last tick | 2026-07-25T17:08:43.892613+00:00 (-4.0758%) |
| Risk rails | normal (dd -1.6%) |
| Data source | coinbase-cfm (bar 2026-07-25 16:00:00+00:00) |
| Gross leverage | 2.66x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.1% | +5 |
| ETH perp | +16.8% | +9 |
| BCH perp | +12.6% | +6 |
| ADA perp | +11.6% | +7 |
| ONDO perp | +3.8% | +1 |
| SOL perp | +3.7% | +1 |
| HBAR perp | +3.5% | +1 |
| AVAX perp | +0.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -32.7% | -9 |
| LTC perp | -25.4% | -11 |
| PEPE perp | -19.6% | -7 |
| ZEC perp | -19.2% | -4 |
| NEAR perp | -18.0% | -2 |
| SUI perp | -17.9% | -5 |
| LINK perp | -12.6% | -3 |
| HYPE perp | -11.6% | -2 |
| ENA perp | -8.7% | -2 |
| SHIB perp | -7.4% | -15 |
| BTC perp | -6.4% | -1 |
| BNB perp | -5.7% | -1 |
| DOT perp | -4.9% | -6 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
