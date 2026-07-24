# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9988** (-0.12% since start) |
| Peak / drawdown | 1.0000 / -0.12% |
| Ticks recorded | 13 |
| Last tick | 2026-07-24T12:08:47.042094+00:00 (+0.3336%) |
| Risk rails | normal (dd -0.4%) |
| Data source | coinbase-cfm (bar 2026-07-24 11:00:00+00:00) |
| Gross leverage | 2.44x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +24.0% | +5 |
| BCH perp | +16.9% | +8 |
| HBAR perp | +14.2% | +4 |
| ETH perp | +13.2% | +7 |
| ADA perp | +11.7% | +7 |
| SOL perp | +7.5% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.8% | -10 |
| SUI perp | -22.0% | -6 |
| LTC perp | -18.6% | -8 |
| SHIB perp | -17.9% | -43 |
| LINK perp | -12.7% | -3 |
| BNB perp | -11.4% | -2 |
| XRP perp | -11.1% | -2 |
| NEAR perp | -9.4% | -1 |
| BTC perp | -6.5% | -1 |
| ENA perp | -4.4% | -1 |
| AVAX perp | -3.8% | -6 |
| PEPE perp | -2.8% | -1 |
| DOT perp | -0.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
