# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9047** (-9.53% since start) |
| Peak / drawdown | 1.0141 / -10.79% |
| Ticks recorded | 1366 |
| Last tick | 2026-09-19T08:08:12.147541+00:00 (+0.0451%) |
| Risk rails | normal (dd -10.8%) |
| Data source | coinbase-cfm (bar 2026-09-19 07:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | -0.24% |
| Weeks >= +3% | 12% |
| Best / worst week | +4.18% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +17.3% | +1 |
| SOL perp | +12.4% | +2 |
| XLM perp | +10.6% | +1 |
| DOT perp | +8.6% | +7 |
| AVAX perp | +7.6% | +8 |
| LINK perp | +6.8% | +1 |
| BCH perp | +5.5% | +2 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.8% | -1 |
| LTC perp | -3.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
