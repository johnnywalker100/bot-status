# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8860** (-11.40% since start) |
| Peak / drawdown | 1.0141 / -12.63% |
| Ticks recorded | 595 |
| Last tick | 2026-08-18T00:10:06.986454+00:00 (-0.1794%) |
| Risk rails | brake: drawdown -12.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-17 23:00:00+00:00) |
| Gross leverage | 1.46x |
| Weeks tracked | 4 |
| Average week | -1.04% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +9.8% | +5 |
| XLM perp | +8.9% | +1 |
| ETH perp | +6.5% | +3 |
| AVAX perp | +3.6% | +5 |
| BCH perp | +2.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.8% | -6 |
| BTC perp | -21.8% | -3 |
| NEAR perp | -18.5% | -2 |
| LTC perp | -17.6% | -7 |
| LINK perp | -10.8% | -2 |
| DOT perp | -6.9% | -8 |
| ZEC perp | -5.8% | -1 |
| XRP perp | -5.7% | -1 |
| SOL perp | -4.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
