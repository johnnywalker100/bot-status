# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9008** (-9.92% since start) |
| Peak / drawdown | 1.0141 / -11.17% |
| Ticks recorded | 734 |
| Last tick | 2026-08-23T20:08:21.606368+00:00 (-0.3567%) |
| Risk rails | normal (dd -11.2%) |
| Data source | coinbase-cfm (bar 2026-08-23 19:00:00+00:00) |
| Gross leverage | 0.75x |
| Weeks tracked | 4 |
| Average week | -0.63% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.58% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +11.0% | +1 |
| BTC perp | +8.6% | +1 |
| BNB perp | +7.8% | +1 |
| AAVE perp | +7.7% | +1 |
| LINK perp | +6.4% | +1 |
| DOT perp | +6.1% | +6 |
| BCH perp | +6.0% | +2 |
| ETH perp | +5.4% | +2 |
| SOL perp | +5.3% | +1 |
| ADA perp | +5.0% | +2 |
| AVAX perp | +3.3% | +4 |
| LTC perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
