# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9300** (-7.00% since start) |
| Peak / drawdown | 1.0141 / -8.29% |
| Ticks recorded | 386 |
| Last tick | 2026-08-09T06:08:36.672867+00:00 (+0.2593%) |
| Risk rails | normal (dd -8.3%) |
| Data source | coinbase-cfm (bar 2026-08-09 05:00:00+00:00) |
| Gross leverage | 2.53x |
| Weeks tracked | 2 |
| Average week | +0.32% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.11% |

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
| DOGE perp | -52.7% | -14 |
| BCH perp | -30.1% | -13 |
| BNB perp | -19.4% | -3 |
| DOT perp | -18.3% | -21 |
| ZEC perp | -16.4% | -3 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -7.6% | -11 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
