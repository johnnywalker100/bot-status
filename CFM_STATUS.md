# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8706** (-12.94% since start) |
| Peak / drawdown | 1.0141 / -14.16% |
| Ticks recorded | 1187 |
| Last tick | 2026-09-11T19:08:19.873266+00:00 (-0.0103%) |
| Risk rails | brake: drawdown -14.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-11 18:00:00+00:00) |
| Gross leverage | 0.36x |
| Weeks tracked | 7 |
| Average week | -0.84% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +8.9% | +1 |
| AAVE perp | +7.1% | +1 |
| SOL perp | +5.8% | +1 |
| AVAX perp | +5.1% | +6 |
| ETH perp | +2.9% | +1 |
| DOT perp | +1.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -2.6% | -1 |
| ADA perp | -2.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
