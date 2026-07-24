# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0025** (+0.25% since start) |
| Peak / drawdown | 1.0141 / -1.14% |
| Ticks recorded | 23 |
| Last tick | 2026-07-24T23:08:43.319308+00:00 (+0.0761%) |
| Risk rails | normal (dd -1.2%) |
| Data source | coinbase-cfm (bar 2026-07-24 22:00:00+00:00) |
| Gross leverage | 2.57x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.8% | +6 |
| BCH perp | +16.8% | +8 |
| ETH perp | +14.8% | +8 |
| HBAR perp | +14.1% | +4 |
| ADA perp | +11.4% | +7 |
| SOL perp | +7.4% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.7% | -10 |
| SUI perp | -21.3% | -6 |
| LTC perp | -18.5% | -8 |
| NEAR perp | -18.0% | -2 |
| SHIB perp | -17.9% | -43 |
| LINK perp | -12.5% | -3 |
| BNB perp | -11.3% | -2 |
| XRP perp | -10.9% | -2 |
| BTC perp | -6.4% | -1 |
| AVAX perp | -4.4% | -7 |
| ENA perp | -4.4% | -1 |
| PEPE perp | -2.7% | -1 |
| DOT perp | -1.6% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
