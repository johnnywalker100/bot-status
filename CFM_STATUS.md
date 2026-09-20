# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8990** (-10.10% since start) |
| Peak / drawdown | 1.0141 / -11.35% |
| Ticks recorded | 1393 |
| Last tick | 2026-09-20T12:08:22.293169+00:00 (+0.7640%) |
| Risk rails | normal (dd -11.4%) |
| Data source | coinbase-cfm (bar 2026-09-20 11:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.33% |
| Weeks >= +3% | 12% |
| Best / worst week | +3.52% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.3% | +1 |
| SOL perp | +12.1% | +2 |
| XLM perp | +10.6% | +1 |
| DOT perp | +9.8% | +8 |
| BCH perp | +8.2% | +3 |
| LINK perp | +6.7% | +1 |
| AVAX perp | +5.8% | +5 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
