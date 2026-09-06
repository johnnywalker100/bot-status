# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8923** (-10.77% since start) |
| Peak / drawdown | 1.0141 / -12.01% |
| Ticks recorded | 1054 |
| Last tick | 2026-09-06T06:08:11.140637+00:00 (+0.1772%) |
| Risk rails | normal (dd -12.0%) |
| Data source | coinbase-cfm (bar 2026-09-06 05:00:00+00:00) |
| Gross leverage | 0.68x |
| Weeks tracked | 6 |
| Average week | -0.57% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +11.9% | +2 |
| AVAX perp | +9.5% | +11 |
| BTC perp | +9.0% | +1 |
| BNB perp | +8.5% | +1 |
| AAVE perp | +7.7% | +1 |
| ETH perp | +5.6% | +2 |
| DOGE perp | +5.1% | +1 |
| LTC perp | +3.0% | +1 |
| BCH perp | +2.9% | +1 |
| ADA perp | +2.5% | +1 |
| DOT perp | +2.1% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
