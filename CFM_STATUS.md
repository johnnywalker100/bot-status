# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9269** (-7.31% since start) |
| Peak / drawdown | 1.0141 / -8.60% |
| Ticks recorded | 366 |
| Last tick | 2026-08-08T10:09:01.546593+00:00 (-0.0868%) |
| Risk rails | normal (dd -8.6%) |
| Data source | coinbase-cfm (bar 2026-08-08 09:00:00+00:00) |
| Gross leverage | 2.61x |
| Weeks tracked | 2 |
| Average week | +0.15% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.44% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.0% | +14 |
| AAVE perp | +24.3% | +5 |
| ADA perp | +12.9% | +6 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.1% | +2 |
| LTC perp | +7.4% | +3 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.5% | -12 |
| BNB perp | -38.5% | -6 |
| BCH perp | -32.8% | -14 |
| ZEC perp | -16.4% | -3 |
| DOT perp | -14.1% | -16 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -5.6% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
