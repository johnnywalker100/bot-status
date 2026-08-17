# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8863** (-11.37% since start) |
| Peak / drawdown | 1.0141 / -12.60% |
| Ticks recorded | 593 |
| Last tick | 2026-08-17T22:11:07.083455+00:00 (-0.0103%) |
| Risk rails | brake: drawdown -12.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-17 21:00:00+00:00) |
| Gross leverage | 1.46x |
| Weeks tracked | 4 |
| Average week | -1.03% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.16% |

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
| DOGE perp | -23.8% | -6 |
| BTC perp | -21.8% | -3 |
| NEAR perp | -18.5% | -2 |
| LTC perp | -17.6% | -7 |
| LINK perp | -10.7% | -2 |
| DOT perp | -6.8% | -8 |
| ZEC perp | -5.8% | -1 |
| XRP perp | -5.6% | -1 |
| SOL perp | -4.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
