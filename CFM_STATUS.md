# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9241** (-7.59% since start) |
| Peak / drawdown | 1.0141 / -8.88% |
| Ticks recorded | 401 |
| Last tick | 2026-08-09T21:08:32.079975+00:00 (+0.0824%) |
| Risk rails | normal (dd -8.9%) |
| Data source | coinbase-cfm (bar 2026-08-09 20:00:00+00:00) |
| Gross leverage | 2.46x |
| Weeks tracked | 2 |
| Average week | +0.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.74% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +27.0% | +13 |
| LTC perp | +19.9% | +8 |
| AAVE perp | +14.8% | +3 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.3% | +2 |
| XRP perp | +5.6% | +1 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.5% | -13 |
| BCH perp | -30.3% | -13 |
| BNB perp | -19.7% | -3 |
| DOT perp | -18.4% | -21 |
| ZEC perp | -16.8% | -3 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -7.1% | -10 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
