# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9427** (-5.73% since start) |
| Peak / drawdown | 1.0141 / -7.05% |
| Ticks recorded | 102 |
| Last tick | 2026-07-28T09:08:40.659209+00:00 (-0.0323%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-07-28 08:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +1.98% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.98% / +1.98% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +30.7% | +6 |
| ADA perp | +23.3% | +14 |
| BCH perp | +13.6% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +8.1% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.3% | -13 |
| LTC perp | -34.3% | -14 |
| LINK perp | -26.4% | -6 |
| BNB perp | -24.0% | -4 |
| BTC perp | -20.2% | -3 |
| NEAR perp | -17.8% | -2 |
| ZEC perp | -14.9% | -3 |
| AVAX perp | -13.0% | -19 |
| XLM perp | -9.1% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
