# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9500** (-5.00% since start) |
| Peak / drawdown | 1.0141 / -6.32% |
| Ticks recorded | 242 |
| Last tick | 2026-08-03T05:16:32.861632+00:00 (-0.0966%) |
| Risk rails | normal (dd -6.3%) |
| Data source | coinbase-cfm (bar 2026-08-03 04:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 2 |
| Average week | +1.38% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +1.02% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.2% | +16 |
| XLM perp | +27.0% | +3 |
| SOL perp | +15.3% | +4 |
| ADA perp | +9.7% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +3.3% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.4% | -16 |
| BNB perp | -36.8% | -6 |
| DOGE perp | -33.0% | -9 |
| BCH perp | -22.2% | -10 |
| ZEC perp | -20.1% | -4 |
| LINK perp | -17.4% | -4 |
| XRP perp | -16.9% | -3 |
| BTC perp | -13.2% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -3.4% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
