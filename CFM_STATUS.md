# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8439** (-15.61% since start) |
| Peak / drawdown | 1.0141 / -16.78% |
| Ticks recorded | 641 |
| Last tick | 2026-08-19T22:08:53.104233+00:00 (+0.0371%) |
| Risk rails | brake: drawdown -16.8% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-19 21:00:00+00:00) |
| Gross leverage | 1.53x |
| Weeks tracked | 4 |
| Average week | -2.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.79% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +11.4% | +2 |
| XLM perp | +10.2% | +1 |
| BCH perp | +7.6% | +3 |
| BNB perp | +7.5% | +1 |
| ADA perp | +6.8% | +3 |
| AVAX perp | +5.7% | +7 |
| SOL perp | +5.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -26.8% | -6 |
| NEAR perp | -20.8% | -2 |
| LTC perp | -13.9% | -5 |
| LINK perp | -12.7% | -2 |
| BTC perp | -8.2% | -1 |
| ZEC perp | -6.8% | -1 |
| XRP perp | -6.7% | -1 |
| DOT perp | -2.9% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
