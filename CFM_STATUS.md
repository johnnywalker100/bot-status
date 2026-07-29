# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9706** (-2.94% since start) |
| Peak / drawdown | 1.0141 / -4.30% |
| Ticks recorded | 135 |
| Last tick | 2026-07-29T17:09:01.639054+00:00 (-0.2779%) |
| Risk rails | normal (dd -4.3%) |
| Data source | coinbase-cfm (bar 2026-07-29 16:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 1 |
| Average week | +5.00% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.00% / +5.00% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.3% | +4 |
| ADA perp | +18.5% | +11 |
| XLM perp | +17.7% | +2 |
| BCH perp | +13.0% | +6 |
| ETH perp | +9.8% | +5 |
| DOT perp | +8.6% | +11 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.0% | -13 |
| LTC perp | -37.2% | -16 |
| BNB perp | -29.3% | -5 |
| NEAR perp | -24.6% | -3 |
| BTC perp | -19.7% | -3 |
| LINK perp | -17.1% | -4 |
| ZEC perp | -14.3% | -3 |
| AVAX perp | -9.2% | -14 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
