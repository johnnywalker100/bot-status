# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9413** (-5.87% since start) |
| Peak / drawdown | 1.0141 / -7.18% |
| Ticks recorded | 511 |
| Last tick | 2026-08-14T11:17:04.973901+00:00 (+0.8679%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-08-14 10:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 3 |
| Average week | +0.62% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.3% | +3 |
| AAVE perp | +22.9% | +5 |
| AVAX perp | +10.1% | +15 |
| ETH perp | +10.0% | +5 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -33.3% | -5 |
| DOGE perp | -33.2% | -9 |
| BNB perp | -32.1% | -5 |
| NEAR perp | -25.5% | -3 |
| LINK perp | -23.3% | -5 |
| BCH perp | -21.8% | -10 |
| ADA perp | -17.1% | -9 |
| ZEC perp | -15.5% | -3 |
| LTC perp | -14.2% | -6 |
| DOT perp | -8.0% | -10 |
| XRP perp | -5.3% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
