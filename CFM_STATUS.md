# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9244** (-7.56% since start) |
| Peak / drawdown | 1.0141 / -8.85% |
| Ticks recorded | 78 |
| Last tick | 2026-07-27T09:08:39.858385+00:00 (+0.2649%) |
| Risk rails | normal (dd -8.8%) |
| Data source | coinbase-cfm (bar 2026-07-27 08:00:00+00:00) |
| Gross leverage | 2.86x |
| Weeks tracked | 1 |
| Average week | +0.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.00% / +0.00% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +27.3% | +5 |
| ADA perp | +24.9% | +14 |
| XLM perp | +19.5% | +2 |
| BCH perp | +18.6% | +8 |
| ETH perp | +10.6% | +5 |
| DOT perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.9% | -13 |
| LTC perp | -35.6% | -14 |
| BTC perp | -21.1% | -3 |
| LINK perp | -18.9% | -4 |
| BNB perp | -18.6% | -3 |
| ZEC perp | -16.1% | -3 |
| XRP perp | -11.9% | -2 |
| NEAR perp | -9.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
