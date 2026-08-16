# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9120** (-8.80% since start) |
| Peak / drawdown | 1.0141 / -10.07% |
| Ticks recorded | 568 |
| Last tick | 2026-08-16T21:08:29.243077+00:00 (+0.3547%) |
| Risk rails | normal (dd -10.1%) |
| Data source | coinbase-cfm (bar 2026-08-16 20:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 3 |
| Average week | -0.44% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.80% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.7% | +5 |
| XLM perp | +17.2% | +2 |
| ETH perp | +16.5% | +8 |
| SOL perp | +12.3% | +3 |
| AVAX perp | +6.9% | +10 |
| BCH perp | +6.7% | +3 |
| ADA perp | +1.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -48.3% | -7 |
| DOGE perp | -38.3% | -10 |
| NEAR perp | -35.2% | -4 |
| LTC perp | -34.0% | -14 |
| LINK perp | -20.7% | -4 |
| ZEC perp | -16.0% | -3 |
| DOT perp | -11.7% | -14 |
| BNB perp | -6.6% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
