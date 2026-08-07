# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9376** (-6.24% since start) |
| Peak / drawdown | 1.0141 / -7.55% |
| Ticks recorded | 334 |
| Last tick | 2026-08-07T01:08:22.613120+00:00 (+0.1227%) |
| Risk rails | normal (dd -7.4%) |
| Data source | coinbase-cfm (bar 2026-08-07 00:00:00+00:00) |
| Gross leverage | 2.58x |
| Weeks tracked | 2 |
| Average week | +0.72% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -0.30% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.4% | +15 |
| ADA perp | +21.5% | +10 |
| XLM perp | +17.3% | +2 |
| SOL perp | +7.7% | +2 |
| AAVE perp | +4.8% | +1 |
| LTC perp | +2.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -43.2% | -19 |
| BNB perp | -37.9% | -6 |
| DOGE perp | -36.9% | -10 |
| ZEC perp | -16.1% | -3 |
| DOT perp | -13.1% | -15 |
| LINK perp | -13.1% | -3 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -4.8% | -7 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
