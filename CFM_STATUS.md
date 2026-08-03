# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9408** (-5.92% since start) |
| Peak / drawdown | 1.0141 / -7.23% |
| Ticks recorded | 255 |
| Last tick | 2026-08-03T18:09:31.403541+00:00 (+0.3336%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-08-03 17:00:00+00:00) |
| Gross leverage | 3.07x |
| Weeks tracked | 2 |
| Average week | +0.89% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.04% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.8% | +16 |
| XLM perp | +27.4% | +3 |
| SOL perp | +15.7% | +4 |
| ADA perp | +10.2% | +5 |
| AAVE perp | +5.0% | +1 |
| DOT perp | +3.5% | +4 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -37.7% | -6 |
| LTC perp | -37.5% | -16 |
| DOGE perp | -33.7% | -9 |
| BCH perp | -22.8% | -10 |
| ZEC perp | -20.8% | -4 |
| LINK perp | -17.5% | -4 |
| XRP perp | -17.2% | -3 |
| BTC perp | -13.6% | -2 |
| NEAR perp | -9.3% | -1 |
| AVAX perp | -3.5% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
