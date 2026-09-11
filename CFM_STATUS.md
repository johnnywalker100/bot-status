# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8663** (-13.37% since start) |
| Peak / drawdown | 1.0141 / -14.57% |
| Ticks recorded | 1170 |
| Last tick | 2026-09-11T02:08:10.219051+00:00 (-0.0714%) |
| Risk rails | brake: drawdown -14.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-11 01:00:00+00:00) |
| Gross leverage | 0.40x |
| Weeks tracked | 7 |
| Average week | -0.91% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +8.9% | +1 |
| AAVE perp | +7.0% | +1 |
| AVAX perp | +6.0% | +7 |
| SOL perp | +5.7% | +1 |
| ETH perp | +5.7% | +2 |
| DOT perp | +1.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -2.6% | -1 |
| ADA perp | -2.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
