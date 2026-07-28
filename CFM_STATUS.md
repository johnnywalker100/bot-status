# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9406** (-5.94% since start) |
| Peak / drawdown | 1.0141 / -7.25% |
| Ticks recorded | 93 |
| Last tick | 2026-07-28T00:08:43.884723+00:00 (+0.4250%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-07-27 23:00:00+00:00) |
| Gross leverage | 2.90x |
| Weeks tracked | 1 |
| Average week | +1.76% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.76% / +1.76% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +31.2% | +6 |
| ADA perp | +24.9% | +15 |
| XLM perp | +18.2% | +2 |
| BCH perp | +18.0% | +8 |
| ETH perp | +10.0% | +5 |
| DOT perp | +4.8% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -52.4% | -14 |
| LTC perp | -34.2% | -14 |
| LINK perp | -22.2% | -5 |
| BTC perp | -20.3% | -3 |
| BNB perp | -18.0% | -3 |
| ZEC perp | -15.2% | -3 |
| XRP perp | -11.3% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -0.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
