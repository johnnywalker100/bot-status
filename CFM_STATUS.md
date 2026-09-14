# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8767** (-12.33% since start) |
| Peak / drawdown | 1.0141 / -13.56% |
| Ticks recorded | 1259 |
| Last tick | 2026-09-14T20:08:46.522930+00:00 (+0.2039%) |
| Risk rails | brake: drawdown -13.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-09-14 19:00:00+00:00) |
| Gross leverage | 0.43x |
| Weeks tracked | 8 |
| Average week | -0.65% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| BTC perp | +9.0% | +1 |
| AAVE perp | +7.5% | +1 |
| SOL perp | +5.9% | +1 |
| AVAX perp | +5.2% | +6 |
| ETH perp | +2.9% | +1 |
| DOT perp | +2.3% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.8% | -1 |
| BCH perp | -2.6% | -1 |
| ADA perp | -2.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
