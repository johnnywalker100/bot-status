# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0092** (+0.92% since start) |
| Peak / drawdown | 1.0066 / +0.26% |
| Ticks recorded | 15 |
| Last tick | 2026-07-24T14:08:52.423305+00:00 (+0.2555%) |
| Risk rails | normal (dd +0.0%) |
| Data source | coinbase-cfm (bar 2026-07-24 13:00:00+00:00) |
| Gross leverage | 2.50x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.5% | +5 |
| BCH perp | +16.7% | +8 |
| ETH perp | +14.8% | +8 |
| HBAR perp | +14.0% | +4 |
| ADA perp | +11.4% | +7 |
| SOL perp | +7.4% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.1% | -10 |
| SUI perp | -21.5% | -6 |
| LTC perp | -18.4% | -8 |
| NEAR perp | -18.4% | -2 |
| SHIB perp | -18.0% | -44 |
| LINK perp | -12.4% | -3 |
| BNB perp | -11.1% | -2 |
| XRP perp | -10.8% | -2 |
| BTC perp | -6.4% | -1 |
| ENA perp | -4.3% | -1 |
| AVAX perp | -3.7% | -6 |
| PEPE perp | -2.7% | -1 |
| DOT perp | -0.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
