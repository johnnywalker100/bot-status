# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8924** (-10.76% since start) |
| Peak / drawdown | 1.0141 / -12.00% |
| Ticks recorded | 1050 |
| Last tick | 2026-09-06T02:08:13.344906+00:00 (+0.1554%) |
| Risk rails | normal (dd -12.0%) |
| Data source | coinbase-cfm (bar 2026-09-06 01:00:00+00:00) |
| Gross leverage | 0.68x |
| Weeks tracked | 6 |
| Average week | -0.57% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +11.7% | +2 |
| AVAX perp | +9.5% | +11 |
| BTC perp | +9.0% | +1 |
| BNB perp | +8.6% | +1 |
| AAVE perp | +7.8% | +1 |
| ETH perp | +5.6% | +2 |
| DOGE perp | +5.1% | +1 |
| LTC perp | +3.1% | +1 |
| BCH perp | +2.9% | +1 |
| ADA perp | +2.5% | +1 |
| DOT perp | +2.1% | +2 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
