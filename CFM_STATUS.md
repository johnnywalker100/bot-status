# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9075** (-9.25% since start) |
| Peak / drawdown | 1.0141 / -10.52% |
| Ticks recorded | 1477 |
| Last tick | 2026-09-24T00:08:29.468794+00:00 (+0.1302%) |
| Risk rails | normal (dd -10.5%) |
| Data source | coinbase-cfm (bar 2026-09-23 23:00:00+00:00) |
| Gross leverage | 0.97x |
| Weeks tracked | 9 |
| Average week | -0.17% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.7% | +1 |
| XLM perp | +11.1% | +1 |
| DOT perp | +10.9% | +9 |
| BNB perp | +8.5% | +1 |
| AAVE perp | +7.6% | +1 |
| BCH perp | +7.5% | +2 |
| LINK perp | +6.8% | +1 |
| SOL perp | +6.4% | +1 |
| ETH perp | +5.9% | +2 |
| DOGE perp | +5.1% | +1 |
| AVAX perp | +4.5% | +4 |
| LTC perp | +3.4% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
