# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8934** (-10.66% since start) |
| Peak / drawdown | 1.0141 / -11.91% |
| Ticks recorded | 746 |
| Last tick | 2026-08-24T08:08:40.235031+00:00 (-0.3005%) |
| Risk rails | normal (dd -11.9%) |
| Data source | coinbase-cfm (bar 2026-08-24 07:00:00+00:00) |
| Gross leverage | 0.66x |
| Weeks tracked | 5 |
| Average week | -0.67% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +8.7% | +1 |
| AAVE perp | +7.9% | +1 |
| BNB perp | +7.8% | +1 |
| LINK perp | +6.4% | +1 |
| DOT perp | +6.1% | +6 |
| BCH perp | +6.0% | +2 |
| ETH perp | +5.5% | +2 |
| SOL perp | +5.3% | +1 |
| AVAX perp | +5.0% | +6 |
| ADA perp | +4.9% | +2 |
| LTC perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
