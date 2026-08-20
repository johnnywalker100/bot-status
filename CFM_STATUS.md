# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8403** (-15.97% since start) |
| Peak / drawdown | 1.0141 / -17.14% |
| Ticks recorded | 660 |
| Last tick | 2026-08-20T17:09:30.812808+00:00 (-0.9120%) |
| Risk rails | brake: drawdown -17.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-20 16:00:00+00:00) |
| Gross leverage | 1.66x |
| Weeks tracked | 4 |
| Average week | -2.29% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -8.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +29.0% | +5 |
| XLM perp | +11.1% | +1 |
| AVAX perp | +10.3% | +12 |
| BCH perp | +8.1% | +3 |
| BNB perp | +7.8% | +1 |
| ADA perp | +7.2% | +3 |
| ETH perp | +5.6% | +2 |
| SOL perp | +5.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -21.0% | -2 |
| DOGE perp | -19.7% | -4 |
| LTC perp | -17.3% | -6 |
| BTC perp | -8.7% | -1 |
| XRP perp | -7.8% | -1 |
| LINK perp | -6.4% | -1 |
| DOT perp | -1.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
