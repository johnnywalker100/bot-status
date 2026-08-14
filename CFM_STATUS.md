# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9429** (-5.71% since start) |
| Peak / drawdown | 1.0141 / -7.03% |
| Ticks recorded | 518 |
| Last tick | 2026-08-14T18:12:17.482751+00:00 (+0.3974%) |
| Risk rails | normal (dd -7.0%) |
| Data source | coinbase-cfm (bar 2026-08-14 17:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 3 |
| Average week | +0.67% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.4% | +3 |
| AAVE perp | +22.9% | +5 |
| AVAX perp | +10.2% | +15 |
| ETH perp | +9.9% | +5 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -33.4% | -5 |
| DOGE perp | -33.3% | -9 |
| BNB perp | -32.1% | -5 |
| NEAR perp | -25.4% | -3 |
| LINK perp | -23.6% | -5 |
| BCH perp | -21.4% | -10 |
| ADA perp | -19.0% | -10 |
| ZEC perp | -15.6% | -3 |
| LTC perp | -13.9% | -6 |
| DOT perp | -8.1% | -10 |
| XRP perp | -5.3% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
