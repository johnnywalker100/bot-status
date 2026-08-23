# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8922** (-10.78% since start) |
| Peak / drawdown | 1.0141 / -12.02% |
| Ticks recorded | 726 |
| Last tick | 2026-08-23T12:08:23.974828+00:00 (+0.0914%) |
| Risk rails | normal (dd -12.0%) |
| Data source | coinbase-cfm (bar 2026-08-23 11:00:00+00:00) |
| Gross leverage | 0.75x |
| Weeks tracked | 4 |
| Average week | -0.87% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.52% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +11.0% | +1 |
| BTC perp | +8.6% | +1 |
| BNB perp | +7.8% | +1 |
| AAVE perp | +7.1% | +1 |
| LINK perp | +6.4% | +1 |
| DOT perp | +6.2% | +6 |
| BCH perp | +6.1% | +2 |
| ETH perp | +5.4% | +2 |
| SOL perp | +5.3% | +1 |
| ADA perp | +5.0% | +2 |
| AVAX perp | +3.4% | +4 |
| LTC perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
