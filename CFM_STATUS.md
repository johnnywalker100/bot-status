# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9341** (-6.59% since start) |
| Peak / drawdown | 1.0141 / -7.89% |
| Ticks recorded | 507 |
| Last tick | 2026-08-14T07:08:24.722332+00:00 (+0.5725%) |
| Risk rails | normal (dd -7.9%) |
| Data source | coinbase-cfm (bar 2026-08-14 06:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | +0.36% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.6% | +3 |
| AAVE perp | +23.3% | +5 |
| AVAX perp | +10.2% | +15 |
| ETH perp | +10.0% | +5 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -33.5% | -9 |
| BNB perp | -32.6% | -5 |
| BTC perp | -27.0% | -4 |
| NEAR perp | -25.9% | -3 |
| LINK perp | -23.5% | -5 |
| BCH perp | -22.1% | -10 |
| ADA perp | -17.5% | -9 |
| ZEC perp | -15.6% | -3 |
| LTC perp | -14.3% | -6 |
| DOT perp | -8.1% | -10 |
| XRP perp | -5.4% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
