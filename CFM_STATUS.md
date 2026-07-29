# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9631** (-3.69% since start) |
| Peak / drawdown | 1.0141 / -5.03% |
| Ticks recorded | 125 |
| Last tick | 2026-07-29T07:08:49.007409+00:00 (+0.3939%) |
| Risk rails | normal (dd -5.0%) |
| Data source | coinbase-cfm (bar 2026-07-29 06:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 1 |
| Average week | +4.19% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.19% / +4.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.4% | +4 |
| ADA perp | +18.7% | +11 |
| XLM perp | +18.0% | +2 |
| BCH perp | +13.3% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +9.5% | +12 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.7% | -13 |
| LTC perp | -37.5% | -16 |
| BNB perp | -29.6% | -5 |
| NEAR perp | -25.0% | -3 |
| BTC perp | -20.1% | -3 |
| LINK perp | -17.5% | -4 |
| ZEC perp | -14.5% | -3 |
| AVAX perp | -8.7% | -13 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
