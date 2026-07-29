# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9619** (-3.81% since start) |
| Peak / drawdown | 1.0141 / -5.15% |
| Ticks recorded | 126 |
| Last tick | 2026-07-29T08:08:52.065359+00:00 (-0.1280%) |
| Risk rails | normal (dd -5.2%) |
| Data source | coinbase-cfm (bar 2026-07-29 07:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 1 |
| Average week | +4.06% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.06% / +4.06% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.3% | +4 |
| ADA perp | +18.8% | +11 |
| XLM perp | +18.0% | +2 |
| BCH perp | +13.3% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +9.5% | +12 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.9% | -13 |
| LTC perp | -37.5% | -16 |
| BNB perp | -29.7% | -5 |
| NEAR perp | -24.9% | -3 |
| BTC perp | -20.1% | -3 |
| LINK perp | -17.5% | -4 |
| ZEC perp | -14.5% | -3 |
| AVAX perp | -8.6% | -13 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
