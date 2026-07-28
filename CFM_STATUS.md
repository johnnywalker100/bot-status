# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9433** (-5.67% since start) |
| Peak / drawdown | 1.0141 / -6.98% |
| Ticks recorded | 105 |
| Last tick | 2026-07-28T12:08:47.170339+00:00 (-0.0839%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-07-28 11:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +2.05% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.05% / +2.05% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +30.7% | +6 |
| ADA perp | +23.3% | +14 |
| BCH perp | +13.5% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +8.0% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.2% | -13 |
| LTC perp | -34.6% | -14 |
| LINK perp | -26.3% | -6 |
| BNB perp | -24.0% | -4 |
| BTC perp | -20.2% | -3 |
| NEAR perp | -17.5% | -2 |
| ZEC perp | -14.8% | -3 |
| AVAX perp | -13.0% | -19 |
| XLM perp | -9.0% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
