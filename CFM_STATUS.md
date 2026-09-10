# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8658** (-13.42% since start) |
| Peak / drawdown | 1.0141 / -14.62% |
| Ticks recorded | 1160 |
| Last tick | 2026-09-10T16:08:14.794419+00:00 (-0.2552%) |
| Risk rails | brake: drawdown -14.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-10 15:00:00+00:00) |
| Gross leverage | 0.47x |
| Weeks tracked | 7 |
| Average week | -0.92% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +8.9% | +1 |
| AAVE perp | +7.0% | +1 |
| SOL perp | +5.7% | +1 |
| ETH perp | +5.6% | +2 |
| AVAX perp | +5.2% | +6 |
| DOGE perp | +4.8% | +1 |
| LTC perp | +3.0% | +1 |
| BCH perp | +2.6% | +1 |
| ADA perp | +2.4% | +1 |
| DOT perp | +1.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
