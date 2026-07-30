# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9430** (-5.70% since start) |
| Peak / drawdown | 1.0141 / -7.01% |
| Ticks recorded | 149 |
| Last tick | 2026-07-30T07:08:40.228854+00:00 (-0.0443%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-07-30 06:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +2.02% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.02% / +2.02% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.5% | +13 |
| AAVE perp | +20.2% | +4 |
| ETH perp | +16.1% | +8 |
| DOT perp | +13.8% | +17 |
| XLM perp | +9.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.5% | -12 |
| LTC perp | -38.6% | -16 |
| NEAR perp | -26.0% | -3 |
| ZEC perp | -25.1% | -5 |
| BNB perp | -24.4% | -4 |
| LINK perp | -17.6% | -4 |
| BTC perp | -13.6% | -2 |
| BCH perp | -8.9% | -4 |
| AVAX perp | -7.5% | -11 |
| XRP perp | -5.7% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
