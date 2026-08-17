# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8892** (-11.08% since start) |
| Peak / drawdown | 1.0141 / -12.32% |
| Ticks recorded | 588 |
| Last tick | 2026-08-17T17:08:28.682818+00:00 (+0.0283%) |
| Risk rails | brake: drawdown -12.3% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-17 16:00:00+00:00) |
| Gross leverage | 1.48x |
| Weeks tracked | 4 |
| Average week | -0.95% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.84% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +9.8% | +5 |
| XLM perp | +8.9% | +1 |
| ETH perp | +6.4% | +3 |
| AVAX perp | +3.5% | +5 |
| BCH perp | +2.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.7% | -6 |
| BTC perp | -21.6% | -3 |
| LTC perp | -20.0% | -8 |
| NEAR perp | -18.3% | -2 |
| LINK perp | -10.7% | -2 |
| DOT perp | -6.8% | -8 |
| ZEC perp | -5.7% | -1 |
| XRP perp | -5.6% | -1 |
| SOL perp | -4.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
