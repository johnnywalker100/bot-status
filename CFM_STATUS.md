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
| Ticks recorded | 338 |
| Last tick | 2026-08-07T05:08:54.557195+00:00 (+0.3540%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-08-07 04:00:00+00:00) |
| Gross leverage | 2.57x |
| Weeks tracked | 2 |
| Average week | +0.90% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.06% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.2% | +15 |
| ADA perp | +21.3% | +10 |
| XLM perp | +17.0% | +2 |
| SOL perp | +7.7% | +2 |
| AAVE perp | +4.8% | +1 |
| LTC perp | +2.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -43.1% | -19 |
| BNB perp | -37.4% | -6 |
| DOGE perp | -36.7% | -10 |
| ZEC perp | -16.0% | -3 |
| DOT perp | -13.0% | -15 |
| LINK perp | -13.0% | -3 |
| NEAR perp | -8.7% | -1 |
| AVAX perp | -5.4% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
