# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8436** (-15.64% since start) |
| Peak / drawdown | 1.0141 / -16.81% |
| Ticks recorded | 640 |
| Last tick | 2026-08-19T21:09:06.590625+00:00 (-1.6254%) |
| Risk rails | brake: drawdown -16.8% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 20:00:00+00:00) |
| Gross leverage | 1.53x |
| Weeks tracked | 4 |
| Average week | -2.20% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.83% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +11.5% | +2 |
| XLM perp | +10.1% | +1 |
| ADA perp | +8.9% | +4 |
| BNB perp | +7.5% | +1 |
| AVAX perp | +5.7% | +7 |
| SOL perp | +5.1% | +1 |
| BCH perp | +5.0% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -26.8% | -6 |
| NEAR perp | -20.7% | -2 |
| LTC perp | -13.9% | -5 |
| LINK perp | -12.9% | -2 |
| BTC perp | -8.3% | -1 |
| ZEC perp | -6.8% | -1 |
| XRP perp | -6.6% | -1 |
| DOT perp | -2.8% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
