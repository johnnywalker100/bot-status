# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8974** (-10.26% since start) |
| Peak / drawdown | 1.0141 / -11.51% |
| Ticks recorded | 753 |
| Last tick | 2026-08-24T15:09:05.599907+00:00 (+0.3810%) |
| Risk rails | normal (dd -11.5%) |
| Data source | coinbase-cfm (bar 2026-08-24 14:00:00+00:00) |
| Gross leverage | 0.59x |
| Weeks tracked | 5 |
| Average week | -0.58% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +8.9% | +1 |
| BNB perp | +7.9% | +1 |
| AAVE perp | +7.6% | +1 |
| LINK perp | +6.5% | +1 |
| BCH perp | +6.2% | +2 |
| DOT perp | +6.1% | +6 |
| SOL perp | +5.4% | +1 |
| AVAX perp | +5.1% | +6 |
| ETH perp | +2.8% | +1 |
| ADA perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
