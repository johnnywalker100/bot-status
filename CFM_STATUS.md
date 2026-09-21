# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9496** (-5.04% since start) |
| Peak / drawdown | 1.0141 / -6.36% |
| Ticks recorded | 1418 |
| Last tick | 2026-09-21T13:08:37.480839+00:00 (+0.2664%) |
| Risk rails | normal (dd -6.4%) |
| Data source | coinbase-cfm (bar 2026-09-21 12:00:00+00:00) |
| Gross leverage | 0.95x |
| Weeks tracked | 9 |
| Average week | +0.34% |
| Weeks >= +3% | 22% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.2% | +1 |
| SOL perp | +12.4% | +2 |
| XLM perp | +11.0% | +1 |
| DOT perp | +10.0% | +8 |
| AAVE perp | +7.8% | +1 |
| LINK perp | +6.9% | +1 |
| AVAX perp | +6.0% | +5 |
| ETH perp | +5.8% | +2 |
| BCH perp | +5.7% | +2 |
| LTC perp | +3.3% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -9.9% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
