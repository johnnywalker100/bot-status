# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9258** (-7.42% since start) |
| Peak / drawdown | 1.0141 / -8.71% |
| Ticks recorded | 88 |
| Last tick | 2026-07-27T19:08:40.358693+00:00 (+0.1050%) |
| Risk rails | normal (dd -8.7%) |
| Data source | coinbase-cfm (bar 2026-07-27 18:00:00+00:00) |
| Gross leverage | 2.90x |
| Weeks tracked | 1 |
| Average week | +0.16% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.16% / +0.16% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +26.8% | +5 |
| ADA perp | +25.8% | +15 |
| BCH perp | +20.9% | +9 |
| XLM perp | +19.1% | +2 |
| ETH perp | +10.5% | +5 |
| DOT perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.5% | -13 |
| LTC perp | -35.1% | -14 |
| LINK perp | -23.3% | -5 |
| BTC perp | -21.0% | -3 |
| BNB perp | -18.7% | -3 |
| ZEC perp | -15.7% | -3 |
| XRP perp | -11.8% | -2 |
| NEAR perp | -9.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
