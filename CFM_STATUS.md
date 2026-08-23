# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9054** (-9.46% since start) |
| Peak / drawdown | 1.0141 / -10.72% |
| Ticks recorded | 714 |
| Last tick | 2026-08-23T00:08:51.820440+00:00 (+0.2163%) |
| Risk rails | normal (dd -10.7%) |
| Data source | coinbase-cfm (bar 2026-08-22 23:00:00+00:00) |
| Gross leverage | 0.97x |
| Weeks tracked | 4 |
| Average week | -0.51% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +14.0% | +2 |
| XLM perp | +10.8% | +1 |
| BCH perp | +9.1% | +3 |
| BTC perp | +8.5% | +1 |
| BNB perp | +7.7% | +1 |
| DOT perp | +7.2% | +7 |
| LINK perp | +6.5% | +1 |
| ETH perp | +5.4% | +2 |
| SOL perp | +5.2% | +1 |
| ADA perp | +5.0% | +2 |
| AVAX perp | +4.1% | +5 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.4% | -1 |
| LTC perp | -2.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
