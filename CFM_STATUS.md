# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9293** (-7.07% since start) |
| Peak / drawdown | 1.0141 / -8.36% |
| Ticks recorded | 387 |
| Last tick | 2026-08-09T07:08:23.042367+00:00 (-0.0768%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-08-09 06:00:00+00:00) |
| Gross leverage | 2.54x |
| Weeks tracked | 2 |
| Average week | +0.28% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.18% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +26.8% | +13 |
| LTC perp | +19.8% | +8 |
| AAVE perp | +19.7% | +4 |
| XLM perp | +8.8% | +1 |
| SOL perp | +8.2% | +2 |
| XRP perp | +5.6% | +1 |
| ADA perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.8% | -14 |
| BCH perp | -30.1% | -13 |
| BNB perp | -19.5% | -3 |
| DOT perp | -18.3% | -21 |
| ZEC perp | -16.5% | -3 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -7.7% | -11 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
