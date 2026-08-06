# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9433** (-5.67% since start) |
| Peak / drawdown | 1.0141 / -6.99% |
| Ticks recorded | 329 |
| Last tick | 2026-08-06T20:08:45.187177+00:00 (+0.2482%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-08-06 19:00:00+00:00) |
| Gross leverage | 2.84x |
| Weeks tracked | 2 |
| Average week | +1.02% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.30% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.4% | +17 |
| XLM perp | +25.6% | +3 |
| AAVE perp | +18.9% | +4 |
| ADA perp | +8.6% | +4 |
| SOL perp | +7.7% | +2 |
| LTC perp | +7.2% | +3 |
| BTC perp | +6.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -40.7% | -18 |
| DOGE perp | -36.4% | -10 |
| NEAR perp | -26.3% | -3 |
| ZEC perp | -20.9% | -4 |
| BNB perp | -18.8% | -3 |
| DOT perp | -14.0% | -16 |
| XRP perp | -11.0% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
