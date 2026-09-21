# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9471** (-5.29% since start) |
| Peak / drawdown | 1.0141 / -6.61% |
| Ticks recorded | 1417 |
| Last tick | 2026-09-21T12:08:12.061018+00:00 (+0.0128%) |
| Risk rails | normal (dd -6.6%) |
| Data source | coinbase-cfm (bar 2026-09-21 11:00:00+00:00) |
| Gross leverage | 0.90x |
| Weeks tracked | 9 |
| Average week | +0.31% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.4% | +1 |
| SOL perp | +12.3% | +2 |
| XLM perp | +11.2% | +1 |
| DOT perp | +10.1% | +8 |
| AAVE perp | +7.7% | +1 |
| LINK perp | +6.9% | +1 |
| AVAX perp | +6.0% | +5 |
| ETH perp | +5.8% | +2 |
| BCH perp | +5.6% | +2 |
| LTC perp | +3.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
