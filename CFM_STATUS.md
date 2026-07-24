# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **1.0067** (+0.67% since start) |
| Peak / drawdown | 1.0141 / -0.73% |
| Ticks recorded | 19 |
| Last tick | 2026-07-24T18:08:48.578297+00:00 (-0.4066%) |
| Risk rails | normal (dd -0.3%) |
| Data source | coinbase-cfm (bar 2026-07-24 17:00:00+00:00) |
| Gross leverage | 2.54x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.9% | +6 |
| BCH perp | +16.6% | +8 |
| ETH perp | +14.8% | +8 |
| HBAR perp | +14.0% | +4 |
| ADA perp | +11.3% | +7 |
| SOL perp | +7.3% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.2% | -10 |
| SUI perp | -21.2% | -6 |
| LTC perp | -18.3% | -8 |
| SHIB perp | -18.2% | -44 |
| NEAR perp | -18.0% | -2 |
| LINK perp | -12.4% | -3 |
| BNB perp | -11.1% | -2 |
| XRP perp | -10.8% | -2 |
| BTC perp | -6.3% | -1 |
| ENA perp | -4.3% | -1 |
| AVAX perp | -4.3% | -7 |
| PEPE perp | -2.7% | -1 |
| DOT perp | -0.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
