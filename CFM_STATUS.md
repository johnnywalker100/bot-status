# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0141** (+1.41% since start) |
| Peak / drawdown | 1.0092 / +0.49% |
| Ticks recorded | 16 |
| Last tick | 2026-07-24T15:08:43.017079+00:00 (+0.4917%) |
| Risk rails | normal (dd +0.0%) |
| Data source | coinbase-cfm (bar 2026-07-24 14:00:00+00:00) |
| Gross leverage | 2.53x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.1% | +6 |
| BCH perp | +16.6% | +8 |
| ETH perp | +14.7% | +8 |
| HBAR perp | +14.0% | +4 |
| ADA perp | +11.4% | +7 |
| SOL perp | +7.3% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.0% | -10 |
| SUI perp | -21.3% | -6 |
| LTC perp | -18.3% | -8 |
| SHIB perp | -18.0% | -44 |
| NEAR perp | -17.9% | -2 |
| LINK perp | -12.4% | -3 |
| BNB perp | -11.1% | -2 |
| XRP perp | -10.8% | -2 |
| BTC perp | -6.3% | -1 |
| ENA perp | -4.3% | -1 |
| AVAX perp | -3.7% | -6 |
| PEPE perp | -2.7% | -1 |
| DOT perp | -0.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
