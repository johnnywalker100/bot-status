# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9419** (-5.81% since start) |
| Peak / drawdown | 1.0141 / -7.12% |
| Ticks recorded | 252 |
| Last tick | 2026-08-03T15:11:28.551278+00:00 (-0.4693%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-08-03 14:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 2 |
| Average week | +0.95% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.16% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.7% | +16 |
| XLM perp | +27.3% | +3 |
| SOL perp | +15.6% | +4 |
| ADA perp | +10.2% | +5 |
| AAVE perp | +5.0% | +1 |
| DOT perp | +3.5% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.7% | -16 |
| BNB perp | -37.6% | -6 |
| DOGE perp | -33.6% | -9 |
| BCH perp | -24.6% | -11 |
| ZEC perp | -20.8% | -4 |
| LINK perp | -17.6% | -4 |
| XRP perp | -17.2% | -3 |
| NEAR perp | -9.3% | -1 |
| BTC perp | -6.8% | -1 |
| AVAX perp | -3.5% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
