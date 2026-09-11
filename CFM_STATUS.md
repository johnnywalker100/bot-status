# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8757** (-12.43% since start) |
| Peak / drawdown | 1.0141 / -13.65% |
| Ticks recorded | 1183 |
| Last tick | 2026-09-11T15:08:42.680363+00:00 (-0.2246%) |
| Risk rails | brake: drawdown -13.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-11 14:00:00+00:00) |
| Gross leverage | 0.37x |
| Weeks tracked | 7 |
| Average week | -0.76% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +9.0% | +1 |
| AAVE perp | +7.3% | +1 |
| SOL perp | +5.9% | +1 |
| AVAX perp | +5.3% | +6 |
| ETH perp | +3.0% | +1 |
| DOT perp | +1.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -2.7% | -1 |
| ADA perp | -2.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
