# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9376** (-6.24% since start) |
| Peak / drawdown | 1.0141 / -7.55% |
| Ticks recorded | 160 |
| Last tick | 2026-07-30T18:08:51.217884+00:00 (-0.1544%) |
| Risk rails | normal (dd -7.5%) |
| Data source | coinbase-cfm (bar 2026-07-30 17:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +1.43% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.43% / +1.43% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.1% | +12 |
| AAVE perp | +21.3% | +4 |
| ETH perp | +16.4% | +8 |
| DOT perp | +13.2% | +16 |
| XLM perp | +9.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.4% | -12 |
| LTC perp | -38.7% | -16 |
| NEAR perp | -26.8% | -3 |
| BNB perp | -25.4% | -4 |
| ZEC perp | -25.2% | -5 |
| LINK perp | -18.1% | -4 |
| BTC perp | -13.8% | -2 |
| AVAX perp | -8.3% | -12 |
| BCH perp | -7.0% | -3 |
| XRP perp | -5.8% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
