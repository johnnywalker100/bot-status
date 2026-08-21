# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8623** (-13.77% since start) |
| Peak / drawdown | 1.0141 / -14.97% |
| Ticks recorded | 673 |
| Last tick | 2026-08-21T06:08:45.976812+00:00 (+0.8431%) |
| Risk rails | brake: drawdown -15.0% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-21 05:00:00+00:00) |
| Gross leverage | 1.23x |
| Weeks tracked | 4 |
| Average week | -1.69% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -5.79% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.5% | +4 |
| BNB perp | +15.4% | +2 |
| SOL perp | +10.6% | +2 |
| AVAX perp | +8.6% | +10 |
| BCH perp | +8.4% | +3 |
| ADA perp | +7.3% | +3 |
| DOT perp | +6.9% | +7 |
| LINK perp | +6.4% | +1 |
| ETH perp | +5.5% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -14.5% | -3 |
| NEAR perp | -10.6% | -1 |
| LTC perp | -5.6% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
