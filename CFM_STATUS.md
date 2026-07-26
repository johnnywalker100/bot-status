# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9292** (-7.08% since start) |
| Peak / drawdown | 1.0141 / -8.37% |
| Ticks recorded | 51 |
| Last tick | 2026-07-26T06:08:40.756091+00:00 (-0.2264%) |
| Risk rails | normal (dd -8.2%) |
| Data source | coinbase-cfm (bar 2026-07-26 05:00:00+00:00) |
| Gross leverage | 3.09x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +24.8% | +14 |
| AVAX perp | +19.6% | +27 |
| AAVE perp | +14.8% | +3 |
| ETH perp | +14.1% | +7 |
| XLM perp | +9.5% | +1 |
| BCH perp | +9.0% | +4 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -43.3% | -11 |
| LTC perp | -37.6% | -15 |
| NEAR perp | -28.9% | -3 |
| LINK perp | -22.6% | -5 |
| ZEC perp | -21.0% | -4 |
| BTC perp | -20.7% | -3 |
| XRP perp | -17.7% | -3 |
| BNB perp | -12.3% | -2 |
| DOT perp | -8.8% | -10 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
