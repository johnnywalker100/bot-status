# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9411** (-5.89% since start) |
| Peak / drawdown | 1.0141 / -7.20% |
| Ticks recorded | 153 |
| Last tick | 2026-07-30T11:08:40.353277+00:00 (+0.3042%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-07-30 10:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +1.81% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.81% / +1.81% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.6% | +13 |
| AAVE perp | +20.7% | +4 |
| ETH perp | +16.3% | +8 |
| DOT perp | +13.8% | +17 |
| XLM perp | +9.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.5% | -12 |
| LTC perp | -40.7% | -17 |
| NEAR perp | -26.3% | -3 |
| ZEC perp | -25.2% | -5 |
| BNB perp | -25.0% | -4 |
| LINK perp | -17.8% | -4 |
| BTC perp | -13.7% | -2 |
| BCH perp | -8.9% | -4 |
| AVAX perp | -7.5% | -11 |
| XRP perp | -5.7% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
