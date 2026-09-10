# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8756** (-12.44% since start) |
| Peak / drawdown | 1.0141 / -13.66% |
| Ticks recorded | 1152 |
| Last tick | 2026-09-10T08:08:24.587246+00:00 (-0.0772%) |
| Risk rails | brake: drawdown -13.7% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-10 07:00:00+00:00) |
| Gross leverage | 0.47x |
| Weeks tracked | 7 |
| Average week | -0.76% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +8.9% | +1 |
| AAVE perp | +7.1% | +1 |
| SOL perp | +5.8% | +1 |
| ETH perp | +5.6% | +2 |
| AVAX perp | +5.3% | +6 |
| DOGE perp | +4.9% | +1 |
| LTC perp | +3.0% | +1 |
| BCH perp | +2.8% | +1 |
| ADA perp | +2.4% | +1 |
| DOT perp | +1.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
