# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9222** (-7.78% since start) |
| Peak / drawdown | 1.0141 / -9.06% |
| Ticks recorded | 1401 |
| Last tick | 2026-09-20T20:08:11.874364+00:00 (+0.8421%) |
| Risk rails | normal (dd -9.1%) |
| Data source | coinbase-cfm (bar 2026-09-20 19:00:00+00:00) |
| Gross leverage | 0.80x |
| Weeks tracked | 8 |
| Average week | +0.01% |
| Weeks >= +3% | 12% |
| Best / worst week | +6.19% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +16.5% | +1 |
| SOL perp | +12.0% | +2 |
| XLM perp | +10.7% | +1 |
| DOT perp | +10.1% | +8 |
| BCH perp | +8.2% | +3 |
| LINK perp | +6.8% | +1 |
| AVAX perp | +4.9% | +4 |
| LTC perp | +3.2% | +1 |
| ETH perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -4.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
