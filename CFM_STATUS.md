# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8798** (-12.02% since start) |
| Peak / drawdown | 1.0141 / -13.24% |
| Ticks recorded | 675 |
| Last tick | 2026-08-21T08:08:36.684629+00:00 (+1.6247%) |
| Risk rails | brake: drawdown -13.2% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-21 07:00:00+00:00) |
| Gross leverage | 1.16x |
| Weeks tracked | 4 |
| Average week | -1.21% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.87% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +18.1% | +3 |
| BNB perp | +15.3% | +2 |
| SOL perp | +10.3% | +2 |
| BCH perp | +9.0% | +3 |
| ETH perp | +8.1% | +3 |
| AVAX perp | +7.7% | +9 |
| ADA perp | +7.2% | +3 |
| LINK perp | +6.6% | +1 |
| DOT perp | +5.9% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -14.3% | -3 |
| NEAR perp | -10.9% | -1 |
| LTC perp | -2.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
