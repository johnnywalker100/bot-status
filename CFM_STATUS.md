# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9189** (-8.11% since start) |
| Peak / drawdown | 1.0141 / -9.39% |
| Ticks recorded | 289 |
| Last tick | 2026-08-05T04:08:49.658074+00:00 (+0.5583%) |
| Risk rails | normal (dd -9.4%) |
| Data source | coinbase-cfm (bar 2026-08-05 03:00:00+00:00) |
| Gross leverage | 3.10x |
| Weeks tracked | 2 |
| Average week | -0.28% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.29% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.5% | +17 |
| XLM perp | +27.2% | +3 |
| AAVE perp | +19.8% | +4 |
| SOL perp | +16.0% | +4 |
| ADA perp | +14.5% | +7 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +4.3% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.2% | -9 |
| XRP perp | -23.2% | -4 |
| BCH perp | -23.0% | -10 |
| ZEC perp | -22.3% | -4 |
| LTC perp | -21.9% | -9 |
| BNB perp | -19.6% | -3 |
| LINK perp | -17.7% | -4 |
| DOT perp | -15.7% | -17 |
| NEAR perp | -9.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
