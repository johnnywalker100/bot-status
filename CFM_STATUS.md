# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8831** (-11.69% since start) |
| Peak / drawdown | 1.0141 / -12.92% |
| Ticks recorded | 679 |
| Last tick | 2026-08-21T12:11:31.824294+00:00 (-0.6790%) |
| Risk rails | brake: drawdown -12.9% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-21 11:00:00+00:00) |
| Gross leverage | 0.86x |
| Weeks tracked | 4 |
| Average week | -1.12% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.52% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +12.4% | +2 |
| SOL perp | +10.2% | +2 |
| BNB perp | +7.6% | +1 |
| LINK perp | +6.4% | +1 |
| AVAX perp | +6.0% | +7 |
| BCH perp | +5.9% | +2 |
| ETH perp | +5.4% | +2 |
| ADA perp | +4.8% | +2 |
| DOT perp | +4.0% | +4 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.7% | -1 |
| DOGE perp | -9.4% | -2 |
| LTC perp | -2.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
