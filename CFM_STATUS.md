# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9276** (-7.24% since start) |
| Peak / drawdown | 1.0141 / -8.53% |
| Ticks recorded | 385 |
| Last tick | 2026-08-09T05:08:24.921262+00:00 (-0.1294%) |
| Risk rails | normal (dd -8.5%) |
| Data source | coinbase-cfm (bar 2026-08-09 04:00:00+00:00) |
| Gross leverage | 2.53x |
| Weeks tracked | 2 |
| Average week | +0.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.36% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +26.8% | +13 |
| LTC perp | +19.8% | +8 |
| AAVE perp | +19.6% | +4 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.2% | +2 |
| XRP perp | +5.6% | +1 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.8% | -14 |
| BCH perp | -30.2% | -13 |
| BNB perp | -19.4% | -3 |
| DOT perp | -18.4% | -21 |
| ZEC perp | -16.5% | -3 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -7.0% | -10 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
