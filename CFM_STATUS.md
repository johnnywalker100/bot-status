# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9383** (-6.17% since start) |
| Peak / drawdown | 1.0141 / -7.47% |
| Ticks recorded | 49 |
| Last tick | 2026-07-26T04:08:50.326534+00:00 (-0.5054%) |
| Risk rails | normal (dd -7.5%) |
| Data source | coinbase-cfm (bar 2026-07-26 03:00:00+00:00) |
| Gross leverage | 2.99x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +19.4% | +11 |
| AVAX perp | +16.6% | +23 |
| AAVE perp | +14.7% | +3 |
| ETH perp | +12.0% | +6 |
| BCH perp | +11.2% | +5 |
| XLM perp | +9.5% | +1 |
| SOL perp | +4.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.8% | -9 |
| LTC perp | -27.4% | -11 |
| ONDO perp | -20.4% | -5 |
| NEAR perp | -19.2% | -2 |
| ZEC perp | -15.6% | -3 |
| PEPE perp | -15.5% | -5 |
| SUI perp | -15.3% | -4 |
| LINK perp | -13.5% | -3 |
| HYPE perp | -12.5% | -2 |
| ENA perp | -9.2% | -2 |
| BTC perp | -6.9% | -1 |
| BNB perp | -6.1% | -1 |
| XRP perp | -5.9% | -1 |
| HBAR perp | -3.7% | -1 |
| SHIB perp | -2.9% | -5 |
| DOT perp | -2.6% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
