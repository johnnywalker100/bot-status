# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0018** (+0.18% since start) |
| Peak / drawdown | 1.0141 / -1.22% |
| Ticks recorded | 22 |
| Last tick | 2026-07-24T22:08:54.090135+00:00 (-0.5778%) |
| Risk rails | normal (dd -0.6%) |
| Data source | coinbase-cfm (bar 2026-07-24 21:00:00+00:00) |
| Gross leverage | 2.56x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.5% | +6 |
| BCH perp | +16.6% | +8 |
| ETH perp | +14.8% | +8 |
| HBAR perp | +14.3% | +4 |
| ADA perp | +11.4% | +7 |
| SOL perp | +7.3% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.3% | -10 |
| SUI perp | -21.3% | -6 |
| LTC perp | -18.2% | -8 |
| SHIB perp | -18.2% | -44 |
| NEAR perp | -18.0% | -2 |
| LINK perp | -12.3% | -3 |
| BNB perp | -11.4% | -2 |
| XRP perp | -10.8% | -2 |
| BTC perp | -6.4% | -1 |
| ENA perp | -4.4% | -1 |
| AVAX perp | -4.3% | -7 |
| PEPE perp | -2.8% | -1 |
| DOT perp | -1.6% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
