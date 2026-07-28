# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9481** (-5.19% since start) |
| Peak / drawdown | 1.0141 / -6.51% |
| Ticks recorded | 94 |
| Last tick | 2026-07-28T01:08:46.556833+00:00 (+0.7939%) |
| Risk rails | normal (dd -6.4%) |
| Data source | coinbase-cfm (bar 2026-07-28 00:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +2.57% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.57% / +2.57% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +25.5% | +5 |
| ADA perp | +24.3% | +15 |
| BCH perp | +15.6% | +7 |
| ETH perp | +9.8% | +5 |
| DOT perp | +8.7% | +11 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.1% | -14 |
| LTC perp | -33.8% | -14 |
| LINK perp | -26.2% | -6 |
| BNB perp | -23.7% | -4 |
| BTC perp | -19.9% | -3 |
| NEAR perp | -17.6% | -2 |
| ZEC perp | -14.9% | -3 |
| AVAX perp | -12.8% | -19 |
| XLM perp | -9.0% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
