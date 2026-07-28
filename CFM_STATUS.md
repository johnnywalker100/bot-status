# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9477** (-5.23% since start) |
| Peak / drawdown | 1.0141 / -6.55% |
| Ticks recorded | 99 |
| Last tick | 2026-07-28T06:08:39.685621+00:00 (+0.9431%) |
| Risk rails | normal (dd -6.5%) |
| Data source | coinbase-cfm (bar 2026-07-28 05:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +2.53% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.53% / +2.53% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +30.8% | +6 |
| ADA perp | +24.6% | +15 |
| BCH perp | +13.4% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +8.1% | +10 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.6% | -14 |
| LTC perp | -34.1% | -14 |
| LINK perp | -26.3% | -6 |
| BNB perp | -23.8% | -4 |
| BTC perp | -20.1% | -3 |
| NEAR perp | -17.5% | -2 |
| ZEC perp | -14.8% | -3 |
| AVAX perp | -12.8% | -19 |
| XLM perp | -9.1% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
