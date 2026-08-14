# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9298** (-7.02% since start) |
| Peak / drawdown | 1.0141 / -8.31% |
| Ticks recorded | 521 |
| Last tick | 2026-08-14T22:10:01.992205+00:00 (-0.3742%) |
| Risk rails | normal (dd -8.2%); blind 2.0h -> 50% size on resume |
| Data source | coinbase-cfm (bar 2026-08-14 21:00:00+00:00) |
| Gross leverage | 1.44x |
| Weeks tracked | 3 |
| Average week | +0.20% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +9.2% | +2 |
| XLM perp | +8.5% | +1 |
| ETH perp | +6.0% | +3 |
| AVAX perp | +4.8% | +7 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -17.4% | -2 |
| DOGE perp | -15.0% | -4 |
| LINK perp | -14.4% | -3 |
| BTC perp | -13.5% | -2 |
| BNB perp | -13.0% | -2 |
| BCH perp | -10.9% | -5 |
| ADA perp | -9.6% | -5 |
| LTC perp | -7.0% | -3 |
| XRP perp | -5.3% | -1 |
| ZEC perp | -5.3% | -1 |
| DOT perp | -4.1% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
