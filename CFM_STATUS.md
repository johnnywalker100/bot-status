# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8864** (-11.36% since start) |
| Peak / drawdown | 1.0141 / -12.59% |
| Ticks recorded | 619 |
| Last tick | 2026-08-19T00:08:47.580177+00:00 (+0.1847%) |
| Risk rails | brake: drawdown -12.6% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-18 23:00:00+00:00) |
| Gross leverage | 1.45x |
| Weeks tracked | 4 |
| Average week | -1.03% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.15% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +14.8% | +3 |
| ADA perp | +9.8% | +5 |
| XLM perp | +8.7% | +1 |
| BCH perp | +6.9% | +3 |
| BNB perp | +6.8% | +1 |
| SOL perp | +4.3% | +1 |
| ETH perp | +4.3% | +2 |
| AVAX perp | +3.6% | +5 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.7% | -6 |
| BTC perp | -14.6% | -2 |
| XRP perp | -11.3% | -2 |
| LTC perp | -10.0% | -4 |
| NEAR perp | -8.9% | -1 |
| DOT perp | -5.9% | -7 |
| ZEC perp | -5.7% | -1 |
| LINK perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
