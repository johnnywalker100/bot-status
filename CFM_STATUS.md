# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9498** (-5.02% since start) |
| Peak / drawdown | 1.0141 / -6.35% |
| Ticks recorded | 118 |
| Last tick | 2026-07-29T01:08:41.368718+00:00 (+0.2090%) |
| Risk rails | normal (dd -6.3%) |
| Data source | coinbase-cfm (bar 2026-07-29 00:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 1 |
| Average week | +2.75% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.75% / +2.75% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +21.2% | +4 |
| ADA perp | +18.8% | +11 |
| XLM perp | +18.4% | +2 |
| BCH perp | +13.6% | +6 |
| ETH perp | +10.1% | +5 |
| DOT perp | +9.6% | +12 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.5% | -13 |
| LTC perp | -38.8% | -16 |
| BNB perp | -30.1% | -5 |
| NEAR perp | -26.1% | -3 |
| BTC perp | -20.2% | -3 |
| LINK perp | -17.8% | -4 |
| ZEC perp | -14.7% | -3 |
| AVAX perp | -9.0% | -13 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
