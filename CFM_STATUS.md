# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9164** (-8.36% since start) |
| Peak / drawdown | 1.0141 / -9.64% |
| Ticks recorded | 1398 |
| Last tick | 2026-09-20T17:08:11.403935+00:00 (+0.9966%) |
| Risk rails | normal (dd -9.6%) |
| Data source | coinbase-cfm (bar 2026-09-20 16:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.08% |
| Weeks >= +3% | 12% |
| Best / worst week | +5.52% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.8% | +1 |
| SOL perp | +12.0% | +2 |
| XLM perp | +10.8% | +1 |
| DOT perp | +10.2% | +8 |
| BCH perp | +8.3% | +3 |
| LINK perp | +6.9% | +1 |
| AVAX perp | +5.0% | +4 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
