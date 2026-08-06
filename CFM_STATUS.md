# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9426** (-5.74% since start) |
| Peak / drawdown | 1.0141 / -7.05% |
| Ticks recorded | 327 |
| Last tick | 2026-08-06T18:08:33.468077+00:00 (+0.3211%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-08-06 17:00:00+00:00) |
| Gross leverage | 2.79x |
| Weeks tracked | 2 |
| Average week | +0.98% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.23% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.4% | +17 |
| XLM perp | +25.9% | +3 |
| AAVE perp | +18.8% | +4 |
| ADA perp | +8.7% | +4 |
| SOL perp | +7.7% | +2 |
| LTC perp | +7.2% | +3 |
| BTC perp | +6.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -40.9% | -18 |
| DOGE perp | -36.5% | -10 |
| NEAR perp | -26.5% | -3 |
| ZEC perp | -21.0% | -4 |
| BNB perp | -18.8% | -3 |
| DOT perp | -13.9% | -16 |
| XRP perp | -5.5% | -1 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
