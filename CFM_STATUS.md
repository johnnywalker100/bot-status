# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9101** (-8.99% since start) |
| Peak / drawdown | 1.0141 / -10.26% |
| Ticks recorded | 1369 |
| Last tick | 2026-09-19T11:08:11.260164+00:00 (+0.1620%) |
| Risk rails | normal (dd -10.3%) |
| Data source | coinbase-cfm (bar 2026-09-19 10:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.17% |
| Weeks >= +3% | 12% |
| Best / worst week | +4.79% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.9% | +1 |
| SOL perp | +12.3% | +2 |
| XLM perp | +10.6% | +1 |
| DOT perp | +8.6% | +7 |
| AVAX perp | +8.1% | +8 |
| LINK perp | +6.9% | +1 |
| BCH perp | +5.5% | +2 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.8% | -1 |
| LTC perp | -3.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
