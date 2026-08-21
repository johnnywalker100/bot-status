# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8546** (-14.54% since start) |
| Peak / drawdown | 1.0141 / -15.73% |
| Ticks recorded | 669 |
| Last tick | 2026-08-21T02:09:41.544832+00:00 (+0.5791%) |
| Risk rails | brake: drawdown -15.7% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-21 01:00:00+00:00) |
| Gross leverage | 1.59x |
| Weeks tracked | 4 |
| Average week | -1.90% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -6.63% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.4% | +4 |
| SOL perp | +15.7% | +3 |
| BNB perp | +15.5% | +2 |
| XLM perp | +10.8% | +1 |
| AVAX perp | +9.4% | +11 |
| ETH perp | +8.3% | +3 |
| BCH perp | +8.0% | +3 |
| DOT perp | +7.9% | +8 |
| ADA perp | +7.4% | +3 |
| LINK perp | +6.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -20.9% | -2 |
| DOGE perp | -19.3% | -4 |
| LTC perp | -5.7% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
