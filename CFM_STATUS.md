# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8876** (-11.24% since start) |
| Peak / drawdown | 1.0141 / -12.47% |
| Ticks recorded | 594 |
| Last tick | 2026-08-17T23:12:21.256584+00:00 (+0.1452%) |
| Risk rails | brake: drawdown -12.5% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-17 22:00:00+00:00) |
| Gross leverage | 1.48x |
| Weeks tracked | 4 |
| Average week | -0.99% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.02% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +9.8% | +5 |
| XLM perp | +8.9% | +1 |
| ETH perp | +6.4% | +3 |
| AVAX perp | +3.6% | +5 |
| BCH perp | +2.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.7% | -6 |
| BTC perp | -21.7% | -3 |
| LTC perp | -20.0% | -8 |
| NEAR perp | -18.4% | -2 |
| LINK perp | -10.7% | -2 |
| DOT perp | -6.8% | -8 |
| ZEC perp | -5.8% | -1 |
| XRP perp | -5.6% | -1 |
| SOL perp | -4.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
