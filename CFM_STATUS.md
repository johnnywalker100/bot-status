# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8900** (-11.00% since start) |
| Peak / drawdown | 1.0141 / -12.24% |
| Ticks recorded | 1060 |
| Last tick | 2026-09-06T12:08:28.135485+00:00 (+0.0169%) |
| Risk rails | brake: drawdown -12.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-06 11:00:00+00:00) |
| Gross leverage | 0.32x |
| Weeks tracked | 6 |
| Average week | -0.62% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +7.6% | +1 |
| SOL perp | +6.0% | +1 |
| DOGE perp | +5.1% | +1 |
| AVAX perp | +4.3% | +5 |
| LTC perp | +3.1% | +1 |
| ETH perp | +2.8% | +1 |
| ADA perp | +2.5% | +1 |
| DOT perp | +1.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
