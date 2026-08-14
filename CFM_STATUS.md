# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9400** (-6.00% since start) |
| Peak / drawdown | 1.0141 / -7.31% |
| Ticks recorded | 512 |
| Last tick | 2026-08-14T12:13:19.425329+00:00 (-0.1389%) |
| Risk rails | normal (dd -7.3%) |
| Data source | coinbase-cfm (bar 2026-08-14 11:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 3 |
| Average week | +0.57% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.3% | +3 |
| AAVE perp | +22.8% | +5 |
| AVAX perp | +10.1% | +15 |
| ETH perp | +10.0% | +5 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -33.4% | -5 |
| DOGE perp | -33.2% | -9 |
| BNB perp | -32.2% | -5 |
| NEAR perp | -25.5% | -3 |
| LINK perp | -23.4% | -5 |
| BCH perp | -21.8% | -10 |
| ADA perp | -17.2% | -9 |
| ZEC perp | -15.4% | -3 |
| LTC perp | -14.2% | -6 |
| DOT perp | -8.1% | -10 |
| XRP perp | -5.3% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
