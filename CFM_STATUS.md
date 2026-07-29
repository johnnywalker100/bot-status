# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9593** (-4.07% since start) |
| Peak / drawdown | 1.0141 / -5.40% |
| Ticks recorded | 124 |
| Last tick | 2026-07-29T06:32:19.538805+00:00 (-0.4649%) |
| Risk rails | normal (dd -5.4%) |
| Data source | coinbase-cfm (bar 2026-07-29 05:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +3.78% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.78% / +3.78% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.5% | +4 |
| ADA perp | +18.9% | +11 |
| XLM perp | +18.1% | +2 |
| BCH perp | +13.4% | +6 |
| ETH perp | +10.0% | +5 |
| DOT perp | +9.5% | +12 |
| SOL perp | +3.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.0% | -13 |
| LTC perp | -37.8% | -16 |
| BNB perp | -29.7% | -5 |
| NEAR perp | -25.3% | -3 |
| BTC perp | -20.1% | -3 |
| LINK perp | -17.6% | -4 |
| ZEC perp | -14.6% | -3 |
| AVAX perp | -8.7% | -13 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
