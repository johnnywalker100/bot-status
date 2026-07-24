# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9923** (-0.77% since start) |
| Peak / drawdown | 1.0000 / -0.77% |
| Ticks recorded | 3 |
| Last tick | 2026-07-24T01:04:42.876212+00:00 (-0.4158%) |
| Risk rails | normal (dd -0.4%) |
| Data source | coinbase-cfm (bar 2026-07-24 00:00:00+00:00) |
| Gross leverage | 2.45x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.9% | +5 |
| BCH perp | +16.9% | +8 |
| ETH perp | +15.0% | +8 |
| HBAR perp | +14.2% | +4 |
| ADA perp | +11.7% | +7 |
| SOL perp | +7.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.7% | -10 |
| SUI perp | -22.4% | -6 |
| LTC perp | -18.9% | -8 |
| SHIB perp | -17.3% | -42 |
| LINK perp | -12.7% | -3 |
| BNB perp | -11.4% | -2 |
| XRP perp | -11.1% | -2 |
| NEAR perp | -9.5% | -1 |
| BTC perp | -6.5% | -1 |
| ENA perp | -4.5% | -1 |
| AVAX perp | -3.8% | -6 |
| PEPE perp | -2.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
