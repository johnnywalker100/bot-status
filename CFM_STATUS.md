# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9210** (-7.90% since start) |
| Peak / drawdown | 1.0141 / -9.18% |
| Ticks recorded | 282 |
| Last tick | 2026-08-04T21:08:39.112901+00:00 (-0.2889%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-08-04 20:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 2 |
| Average week | -0.17% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.07% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.5% | +15 |
| XLM perp | +18.4% | +2 |
| AAVE perp | +14.7% | +3 |
| SOL perp | +12.1% | +3 |
| ADA perp | +8.4% | +4 |
| AVAX perp | +5.8% | +8 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -38.7% | -6 |
| LTC perp | -36.5% | -15 |
| DOGE perp | -30.5% | -8 |
| ZEC perp | -21.9% | -4 |
| BCH perp | -20.9% | -9 |
| BTC perp | -14.0% | -2 |
| LINK perp | -13.3% | -3 |
| DOT perp | -12.9% | -14 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
