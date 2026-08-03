# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9488** (-5.12% since start) |
| Peak / drawdown | 1.0141 / -6.44% |
| Ticks recorded | 240 |
| Last tick | 2026-08-03T03:18:52.398454+00:00 (+0.0046%) |
| Risk rails | normal (dd -6.4%) |
| Data source | coinbase-cfm (bar 2026-08-03 02:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 2 |
| Average week | +1.32% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.89% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.4% | +16 |
| XLM perp | +27.1% | +3 |
| SOL perp | +15.4% | +4 |
| ADA perp | +9.8% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +3.3% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.5% | -16 |
| BNB perp | -37.0% | -6 |
| DOGE perp | -33.2% | -9 |
| BCH perp | -22.2% | -10 |
| ZEC perp | -20.1% | -4 |
| LINK perp | -17.5% | -4 |
| XRP perp | -16.9% | -3 |
| BTC perp | -13.3% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -3.4% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
