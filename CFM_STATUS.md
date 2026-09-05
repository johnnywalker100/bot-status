# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8887** (-11.13% since start) |
| Peak / drawdown | 1.0141 / -12.36% |
| Ticks recorded | 1047 |
| Last tick | 2026-09-05T23:08:14.319658+00:00 (-0.0922%) |
| Risk rails | brake: drawdown -12.4% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-05 22:00:00+00:00) |
| Gross leverage | 0.36x |
| Weeks tracked | 6 |
| Average week | -0.64% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.6% | +1 |
| SOL perp | +5.8% | +1 |
| DOGE perp | +5.1% | +1 |
| AVAX perp | +4.3% | +5 |
| LTC perp | +3.1% | +1 |
| BCH perp | +2.9% | +1 |
| ETH perp | +2.8% | +1 |
| ADA perp | +2.5% | +1 |
| DOT perp | +2.1% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
