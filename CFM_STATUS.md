# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9392** (-6.08% since start) |
| Peak / drawdown | 1.0141 / -7.39% |
| Ticks recorded | 1500 |
| Last tick | 2026-09-24T23:08:51.068101+00:00 (+0.1558%) |
| Risk rails | normal (dd -7.4%) |
| Data source | coinbase-cfm (bar 2026-09-24 22:00:00+00:00) |
| Gross leverage | 0.89x |
| Weeks tracked | 9 |
| Average week | +0.21% |
| Weeks >= +3% | 11% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.4% | +1 |
| XLM perp | +11.5% | +1 |
| DOT perp | +11.1% | +9 |
| AAVE perp | +7.8% | +1 |
| BCH perp | +7.2% | +2 |
| LINK perp | +7.1% | +1 |
| SOL perp | +6.2% | +1 |
| ETH perp | +5.7% | +2 |
| DOGE perp | +5.1% | +1 |
| AVAX perp | +4.4% | +4 |
| LTC perp | +3.8% | +1 |
| ADA perp | +2.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
