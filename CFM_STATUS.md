# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9067** (-9.33% since start) |
| Peak / drawdown | 1.0141 / -10.59% |
| Ticks recorded | 546 |
| Last tick | 2026-08-15T23:08:27.552102+00:00 (+0.0591%) |
| Risk rails | normal (dd -10.6%) |
| Data source | coinbase-cfm (bar 2026-08-15 22:00:00+00:00) |
| Gross leverage | 2.88x |
| Weeks tracked | 3 |
| Average week | -0.62% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.37% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.8% | +5 |
| XLM perp | +17.4% | +2 |
| AVAX perp | +7.7% | +11 |
| BCH perp | +6.7% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.5% | -10 |
| NEAR perp | -36.0% | -4 |
| BTC perp | -34.8% | -5 |
| LTC perp | -34.0% | -14 |
| BNB perp | -26.9% | -4 |
| LINK perp | -21.0% | -4 |
| ZEC perp | -10.8% | -2 |
| ADA perp | -9.8% | -5 |
| DOT perp | -8.4% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
