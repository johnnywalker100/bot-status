# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9313** (-6.87% since start) |
| Peak / drawdown | 1.0141 / -8.16% |
| Ticks recorded | 50 |
| Last tick | 2026-07-26T05:08:48.476325+00:00 (-0.7478%) |
| Risk rails | normal (dd -8.2%) |
| Data source | coinbase-cfm (bar 2026-07-26 04:00:00+00:00) |
| Gross leverage | 3.01x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +19.6% | +11 |
| AVAX perp | +16.7% | +23 |
| AAVE perp | +14.8% | +3 |
| ETH perp | +12.1% | +6 |
| BCH perp | +11.3% | +5 |
| XLM perp | +9.5% | +1 |
| SOL perp | +4.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -35.4% | -9 |
| LTC perp | -27.6% | -11 |
| ONDO perp | -20.8% | -5 |
| NEAR perp | -19.3% | -2 |
| ZEC perp | -15.7% | -3 |
| PEPE perp | -15.6% | -5 |
| SUI perp | -15.5% | -4 |
| LINK perp | -13.6% | -3 |
| HYPE perp | -12.5% | -2 |
| ENA perp | -9.2% | -2 |
| BTC perp | -6.9% | -1 |
| BNB perp | -6.1% | -1 |
| XRP perp | -5.9% | -1 |
| HBAR perp | -3.8% | -1 |
| DOT perp | -2.6% | -3 |
| SHIB perp | -2.4% | -4 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
