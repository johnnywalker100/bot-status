# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9284** (-7.16% since start) |
| Peak / drawdown | 1.0141 / -8.45% |
| Ticks recorded | 91 |
| Last tick | 2026-07-27T22:08:37.144436+00:00 (+0.5771%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-07-27 21:00:00+00:00) |
| Gross leverage | 2.93x |
| Weeks tracked | 1 |
| Average week | +0.44% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.44% / +0.44% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.7% | +5 |
| ADA perp | +25.6% | +15 |
| BCH perp | +20.8% | +9 |
| XLM perp | +18.9% | +2 |
| ETH perp | +10.4% | +5 |
| DOT perp | +0.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.2% | -13 |
| LTC perp | -35.0% | -14 |
| LINK perp | -23.1% | -5 |
| BTC perp | -20.9% | -3 |
| ZEC perp | -20.9% | -4 |
| BNB perp | -18.5% | -3 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
