# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8774** (-12.26% since start) |
| Peak / drawdown | 1.0141 / -13.48% |
| Ticks recorded | 1336 |
| Last tick | 2026-09-18T01:08:30.351500+00:00 (+0.0390%) |
| Risk rails | brake: drawdown -13.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-18 00:00:00+00:00) |
| Gross leverage | 0.35x |
| Weeks tracked | 8 |
| Average week | -0.64% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| LINK perp | +6.5% | +1 |
| SOL perp | +5.8% | +1 |
| DOT perp | +5.0% | +4 |
| AVAX perp | +4.4% | +5 |
| ETH perp | +2.8% | +1 |
| BCH perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.7% | -1 |
| LTC perp | -3.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
