# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9403** (-5.97% since start) |
| Peak / drawdown | 1.0141 / -7.28% |
| Ticks recorded | 158 |
| Last tick | 2026-07-30T16:08:45.920608+00:00 (-0.4849%) |
| Risk rails | normal (dd -7.3%) |
| Data source | coinbase-cfm (bar 2026-07-30 15:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +1.72% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.72% / +1.72% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.9% | +12 |
| AAVE perp | +21.2% | +4 |
| ETH perp | +16.4% | +8 |
| DOT perp | +13.1% | +16 |
| XLM perp | +9.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.0% | -12 |
| LTC perp | -40.8% | -17 |
| NEAR perp | -26.5% | -3 |
| ZEC perp | -25.3% | -5 |
| BNB perp | -25.2% | -4 |
| LINK perp | -18.1% | -4 |
| BTC perp | -13.8% | -2 |
| AVAX perp | -8.3% | -12 |
| BCH perp | -7.0% | -3 |
| XRP perp | -5.8% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
