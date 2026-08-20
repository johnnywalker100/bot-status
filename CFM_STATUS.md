# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8477** (-15.23% since start) |
| Peak / drawdown | 1.0141 / -16.41% |
| Ticks recorded | 658 |
| Last tick | 2026-08-20T15:10:24.015880+00:00 (-0.2040%) |
| Risk rails | brake: drawdown -16.4% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-20 14:00:00+00:00) |
| Gross leverage | 1.58x |
| Weeks tracked | 4 |
| Average week | -2.08% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.38% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +22.9% | +4 |
| XLM perp | +10.7% | +1 |
| AVAX perp | +9.9% | +12 |
| ADA perp | +9.2% | +4 |
| BCH perp | +7.8% | +3 |
| BNB perp | +7.6% | +1 |
| ETH perp | +5.4% | +2 |
| SOL perp | +5.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -20.4% | -2 |
| DOGE perp | -18.6% | -4 |
| LTC perp | -16.9% | -6 |
| BTC perp | -8.5% | -1 |
| XRP perp | -7.4% | -1 |
| LINK perp | -6.2% | -1 |
| DOT perp | -1.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
