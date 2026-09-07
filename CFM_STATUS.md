# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8862** (-11.38% since start) |
| Peak / drawdown | 1.0141 / -12.62% |
| Ticks recorded | 1074 |
| Last tick | 2026-09-07T02:08:19.256510+00:00 (-0.4854%) |
| Risk rails | brake: drawdown -12.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-07 01:00:00+00:00) |
| Gross leverage | 0.46x |
| Weeks tracked | 7 |
| Average week | -0.59% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +9.0% | +1 |
| AAVE perp | +7.5% | +1 |
| SOL perp | +5.9% | +1 |
| AVAX perp | +5.3% | +6 |
| DOGE perp | +5.1% | +1 |
| LTC perp | +3.1% | +1 |
| BCH perp | +2.9% | +1 |
| ETH perp | +2.8% | +1 |
| ADA perp | +2.5% | +1 |
| DOT perp | +2.2% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
