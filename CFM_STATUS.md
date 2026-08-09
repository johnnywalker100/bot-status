# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9209** (-7.91% since start) |
| Peak / drawdown | 1.0141 / -9.19% |
| Ticks recorded | 395 |
| Last tick | 2026-08-09T15:08:38.940679+00:00 (+0.0120%) |
| Risk rails | normal (dd -9.2%) |
| Data source | coinbase-cfm (bar 2026-08-09 14:00:00+00:00) |
| Gross leverage | 2.48x |
| Weeks tracked | 2 |
| Average week | -0.17% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.08% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +27.2% | +13 |
| LTC perp | +20.1% | +8 |
| AAVE perp | +14.9% | +3 |
| XLM perp | +8.9% | +1 |
| SOL perp | +8.4% | +2 |
| XRP perp | +5.7% | +1 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.7% | -13 |
| BCH perp | -30.7% | -13 |
| BNB perp | -19.8% | -3 |
| DOT perp | -18.5% | -21 |
| ZEC perp | -17.0% | -3 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| AVAX perp | -7.1% | -10 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
