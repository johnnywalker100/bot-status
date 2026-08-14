# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9477** (-5.23% since start) |
| Peak / drawdown | 1.0141 / -6.55% |
| Ticks recorded | 513 |
| Last tick | 2026-08-14T13:11:39.188063+00:00 (+0.8179%) |
| Risk rails | normal (dd -6.6%) |
| Data source | coinbase-cfm (bar 2026-08-14 12:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | +0.85% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.04% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.2% | +3 |
| AAVE perp | +22.5% | +5 |
| AVAX perp | +10.1% | +15 |
| ETH perp | +9.8% | +5 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -33.0% | -5 |
| DOGE perp | -32.9% | -9 |
| BNB perp | -31.8% | -5 |
| NEAR perp | -25.1% | -3 |
| LINK perp | -23.2% | -5 |
| BCH perp | -21.3% | -10 |
| ADA perp | -17.0% | -9 |
| ZEC perp | -15.3% | -3 |
| LTC perp | -14.0% | -6 |
| DOT perp | -8.0% | -10 |
| XRP perp | -5.3% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
