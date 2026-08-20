# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8482** (-15.18% since start) |
| Peak / drawdown | 1.0141 / -16.36% |
| Ticks recorded | 643 |
| Last tick | 2026-08-20T00:11:36.398487+00:00 (-0.0428%) |
| Risk rails | brake: drawdown -16.4% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 23:00:00+00:00) |
| Gross leverage | 1.53x |
| Weeks tracked | 4 |
| Average week | -2.07% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.33% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +11.3% | +2 |
| XLM perp | +10.1% | +1 |
| ADA perp | +8.9% | +4 |
| BCH perp | +7.6% | +3 |
| BNB perp | +7.4% | +1 |
| AVAX perp | +5.6% | +7 |
| SOL perp | +5.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -26.6% | -6 |
| NEAR perp | -20.5% | -2 |
| LTC perp | -13.8% | -5 |
| LINK perp | -12.5% | -2 |
| BTC perp | -8.2% | -1 |
| ZEC perp | -6.7% | -1 |
| XRP perp | -6.5% | -1 |
| DOT perp | -2.8% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
