# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8813** (-11.87% since start) |
| Peak / drawdown | 1.0141 / -13.10% |
| Ticks recorded | 676 |
| Last tick | 2026-08-21T09:10:13.843410+00:00 (+0.1680%) |
| Risk rails | brake: drawdown -13.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-21 08:00:00+00:00) |
| Gross leverage | 0.87x |
| Weeks tracked | 4 |
| Average week | -1.17% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.71% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +12.1% | +2 |
| SOL perp | +10.4% | +2 |
| BNB perp | +7.6% | +1 |
| LINK perp | +6.5% | +1 |
| AVAX perp | +5.9% | +7 |
| BCH perp | +5.9% | +2 |
| ETH perp | +5.4% | +2 |
| DOT perp | +5.0% | +5 |
| ADA perp | +4.8% | +2 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.7% | -1 |
| DOGE perp | -9.5% | -2 |
| LTC perp | -2.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
