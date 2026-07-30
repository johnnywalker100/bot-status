# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9426** (-5.74% since start) |
| Peak / drawdown | 1.0141 / -7.06% |
| Ticks recorded | 156 |
| Last tick | 2026-07-30T14:08:55.755459+00:00 (-0.0241%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-07-30 13:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 1 |
| Average week | +1.97% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.97% / +1.97% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.4% | +12 |
| AAVE perp | +21.1% | +4 |
| ETH perp | +16.3% | +8 |
| DOT perp | +13.9% | +17 |
| XLM perp | +9.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.7% | -12 |
| LTC perp | -40.9% | -17 |
| NEAR perp | -26.3% | -3 |
| ZEC perp | -25.1% | -5 |
| BNB perp | -24.9% | -4 |
| LINK perp | -18.0% | -4 |
| BTC perp | -13.7% | -2 |
| AVAX perp | -8.2% | -12 |
| BCH perp | -6.9% | -3 |
| XRP perp | -5.7% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
