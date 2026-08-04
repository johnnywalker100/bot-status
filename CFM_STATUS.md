# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9458** (-5.42% since start) |
| Peak / drawdown | 1.0141 / -6.74% |
| Ticks recorded | 261 |
| Last tick | 2026-08-04T00:08:51.821164+00:00 (-0.2330%) |
| Risk rails | normal (dd -6.7%) |
| Data source | coinbase-cfm (bar 2026-08-03 23:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 2 |
| Average week | +1.15% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.57% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.5% | +16 |
| XLM perp | +27.2% | +3 |
| SOL perp | +15.6% | +4 |
| ADA perp | +10.2% | +5 |
| AAVE perp | +4.9% | +1 |
| DOT perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -37.4% | -16 |
| BNB perp | -37.4% | -6 |
| DOGE perp | -33.4% | -9 |
| BCH perp | -22.6% | -10 |
| ZEC perp | -20.4% | -4 |
| LINK perp | -17.3% | -4 |
| XRP perp | -17.0% | -3 |
| BTC perp | -13.4% | -2 |
| NEAR perp | -9.2% | -1 |
| AVAX perp | -3.5% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
