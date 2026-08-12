# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9233** (-7.67% since start) |
| Peak / drawdown | 1.0141 / -8.96% |
| Ticks recorded | 466 |
| Last tick | 2026-08-12T14:08:50.694691+00:00 (+1.5289%) |
| Risk rails | normal (dd -8.9%) |
| Data source | coinbase-cfm (bar 2026-08-12 13:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.03% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +32.8% | +16 |
| AAVE perp | +24.1% | +5 |
| LTC perp | +22.1% | +9 |
| AVAX perp | +0.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.6% | -18 |
| BTC perp | -34.4% | -5 |
| DOGE perp | -34.3% | -9 |
| ADA perp | -21.8% | -11 |
| DOT perp | -20.5% | -24 |
| BNB perp | -19.9% | -3 |
| ZEC perp | -15.8% | -3 |
| LINK perp | -14.2% | -3 |
| NEAR perp | -8.8% | -1 |
| XLM perp | -8.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
