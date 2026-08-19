# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8576** (-14.24% since start) |
| Peak / drawdown | 1.0141 / -15.44% |
| Ticks recorded | 639 |
| Last tick | 2026-08-19T20:11:27.504381+00:00 (-0.2008%) |
| Risk rails | brake: drawdown -15.4% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 19:00:00+00:00) |
| Gross leverage | 1.58x |
| Weeks tracked | 4 |
| Average week | -1.81% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -6.30% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +10.9% | +2 |
| XLM perp | +9.7% | +1 |
| ADA perp | +8.5% | +4 |
| BCH perp | +7.3% | +3 |
| BNB perp | +7.2% | +1 |
| AVAX perp | +5.4% | +7 |
| SOL perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -29.8% | -7 |
| NEAR perp | -19.9% | -2 |
| LTC perp | -13.5% | -5 |
| XRP perp | -12.5% | -2 |
| LINK perp | -11.8% | -2 |
| BTC perp | -8.0% | -1 |
| ZEC perp | -6.5% | -1 |
| DOT perp | -2.7% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
