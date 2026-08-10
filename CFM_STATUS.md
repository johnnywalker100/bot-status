# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9340** (-6.60% since start) |
| Peak / drawdown | 1.0141 / -7.90% |
| Ticks recorded | 404 |
| Last tick | 2026-08-10T00:08:34.065250+00:00 (+0.5625%) |
| Risk rails | normal (dd -7.9%) |
| Data source | coinbase-cfm (bar 2026-08-09 23:00:00+00:00) |
| Gross leverage | 2.51x |
| Weeks tracked | 3 |
| Average week | +0.35% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +26.6% | +13 |
| AAVE perp | +19.5% | +4 |
| LTC perp | +19.4% | +8 |
| XLM perp | +8.7% | +1 |
| SOL perp | +8.2% | +2 |
| XRP perp | +5.5% | +1 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.0% | -14 |
| BCH perp | -29.9% | -13 |
| BNB perp | -19.4% | -3 |
| DOT perp | -18.0% | -21 |
| ZEC perp | -16.4% | -3 |
| LINK perp | -8.8% | -2 |
| NEAR perp | -8.6% | -1 |
| AVAX perp | -7.6% | -11 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
