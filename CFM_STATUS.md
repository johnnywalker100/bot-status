# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9753** (-2.47% since start) |
| Peak / drawdown | 1.0141 / -3.83% |
| Ticks recorded | 139 |
| Last tick | 2026-07-29T21:08:45.326315+00:00 (+0.4738%) |
| Risk rails | normal (dd -3.8%) |
| Data source | coinbase-cfm (bar 2026-07-29 20:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +5.51% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.51% / +5.51% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +19.8% | +12 |
| AAVE perp | +19.5% | +4 |
| XLM perp | +17.3% | +2 |
| BCH perp | +14.7% | +7 |
| DOT perp | +10.0% | +13 |
| ETH perp | +9.6% | +5 |
| SOL perp | +3.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -46.1% | -13 |
| LTC perp | -38.6% | -17 |
| BNB perp | -29.0% | -5 |
| NEAR perp | -24.3% | -3 |
| BTC perp | -19.4% | -3 |
| ZEC perp | -18.7% | -4 |
| LINK perp | -16.8% | -4 |
| AVAX perp | -8.4% | -13 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
