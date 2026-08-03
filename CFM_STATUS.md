# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9429** (-5.71% since start) |
| Peak / drawdown | 1.0141 / -7.02% |
| Ticks recorded | 257 |
| Last tick | 2026-08-03T20:08:59.552681+00:00 (-0.0933%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-08-03 19:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 2 |
| Average week | +1.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.26% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.7% | +16 |
| XLM perp | +27.4% | +3 |
| SOL perp | +15.7% | +4 |
| ADA perp | +10.3% | +5 |
| AAVE perp | +4.9% | +1 |
| DOT perp | +3.5% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.6% | -16 |
| BNB perp | -37.6% | -6 |
| DOGE perp | -33.5% | -9 |
| BCH perp | -22.7% | -10 |
| ZEC perp | -20.6% | -4 |
| LINK perp | -17.5% | -4 |
| XRP perp | -17.2% | -3 |
| BTC perp | -13.5% | -2 |
| NEAR perp | -9.2% | -1 |
| AVAX perp | -3.5% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
