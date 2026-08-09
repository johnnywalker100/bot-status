# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9218** (-7.82% since start) |
| Peak / drawdown | 1.0141 / -9.10% |
| Ticks recorded | 398 |
| Last tick | 2026-08-09T18:08:55.629325+00:00 (+0.1930%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-08-09 17:00:00+00:00) |
| Gross leverage | 2.52x |
| Weeks tracked | 2 |
| Average week | -0.12% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.98% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +27.1% | +13 |
| LTC perp | +20.0% | +8 |
| AAVE perp | +19.8% | +4 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.4% | +2 |
| XRP perp | +5.7% | +1 |
| ADA perp | +2.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.8% | -13 |
| BCH perp | -30.6% | -13 |
| BNB perp | -19.8% | -3 |
| DOT perp | -18.4% | -21 |
| ZEC perp | -16.7% | -3 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -7.1% | -10 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
