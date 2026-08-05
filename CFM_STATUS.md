# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9162** (-8.38% since start) |
| Peak / drawdown | 1.0141 / -9.65% |
| Ticks recorded | 290 |
| Last tick | 2026-08-05T05:10:43.911655+00:00 (-0.2888%) |
| Risk rails | normal (dd -9.7%) |
| Data source | coinbase-cfm (bar 2026-08-05 04:00:00+00:00) |
| Gross leverage | 3.12x |
| Weeks tracked | 2 |
| Average week | -0.42% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.57% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.7% | +17 |
| XLM perp | +27.3% | +3 |
| AAVE perp | +20.0% | +4 |
| SOL perp | +16.1% | +4 |
| ADA perp | +14.6% | +7 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +4.4% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.3% | -9 |
| XRP perp | -23.3% | -4 |
| BCH perp | -23.1% | -10 |
| ZEC perp | -22.5% | -4 |
| LTC perp | -22.1% | -9 |
| BNB perp | -19.7% | -3 |
| LINK perp | -17.8% | -4 |
| DOT perp | -15.7% | -17 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
