# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9449** (-5.51% since start) |
| Peak / drawdown | 1.0141 / -6.83% |
| Ticks recorded | 157 |
| Last tick | 2026-07-30T15:08:45.745176+00:00 (+0.2458%) |
| Risk rails | normal (dd -6.8%) |
| Data source | coinbase-cfm (bar 2026-07-30 14:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 1 |
| Average week | +2.22% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.22% / +2.22% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.2% | +12 |
| AAVE perp | +20.8% | +4 |
| ETH perp | +16.2% | +8 |
| DOT perp | +13.0% | +16 |
| XLM perp | +9.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.7% | -12 |
| LTC perp | -40.7% | -17 |
| NEAR perp | -26.2% | -3 |
| ZEC perp | -25.1% | -5 |
| BNB perp | -24.9% | -4 |
| LINK perp | -18.0% | -4 |
| BTC perp | -13.7% | -2 |
| AVAX perp | -8.2% | -12 |
| BCH perp | -7.0% | -3 |
| XRP perp | -5.8% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
