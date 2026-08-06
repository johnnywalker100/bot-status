# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9410** (-5.90% since start) |
| Peak / drawdown | 1.0141 / -7.21% |
| Ticks recorded | 330 |
| Last tick | 2026-08-06T21:08:32.148666+00:00 (-0.2464%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-08-06 20:00:00+00:00) |
| Gross leverage | 2.85x |
| Weeks tracked | 2 |
| Average week | +0.90% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.06% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.4% | +17 |
| XLM perp | +25.6% | +3 |
| AAVE perp | +18.9% | +4 |
| ADA perp | +8.6% | +4 |
| SOL perp | +7.7% | +2 |
| LTC perp | +7.3% | +3 |
| BTC perp | +6.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -40.8% | -18 |
| DOGE perp | -36.6% | -10 |
| NEAR perp | -26.4% | -3 |
| ZEC perp | -21.0% | -4 |
| BNB perp | -18.9% | -3 |
| DOT perp | -14.1% | -16 |
| XRP perp | -11.0% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
