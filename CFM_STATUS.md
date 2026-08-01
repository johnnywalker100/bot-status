# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9732** (-2.68% since start) |
| Peak / drawdown | 1.0141 / -4.03% |
| Ticks recorded | 207 |
| Last tick | 2026-08-01T18:08:43.168957+00:00 (+0.9198%) |
| Risk rails | normal (dd -4.0%) |
| Data source | coinbase-cfm (bar 2026-08-01 17:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 1 |
| Average week | +5.28% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.28% / +5.28% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +18.7% | +4 |
| XLM perp | +17.5% | +2 |
| ETH perp | +15.3% | +8 |
| DOT perp | +14.3% | +18 |
| ADA perp | +14.2% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.0% | -14 |
| BNB perp | -29.6% | -5 |
| LTC perp | -29.4% | -13 |
| BCH perp | -27.7% | -13 |
| ZEC perp | -23.9% | -5 |
| LINK perp | -16.5% | -4 |
| BTC perp | -12.9% | -2 |
| NEAR perp | -8.5% | -1 |
| AVAX perp | -7.8% | -12 |
| SOL perp | -7.4% | -2 |
| XRP perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
