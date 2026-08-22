# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9226** (-7.74% since start) |
| Peak / drawdown | 1.0141 / -9.02% |
| Ticks recorded | 692 |
| Last tick | 2026-08-22T02:10:05.258823+00:00 (+1.7545%) |
| Risk rails | normal (dd -9.0%) |
| Data source | coinbase-cfm (bar 2026-08-22 01:00:00+00:00) |
| Gross leverage | 1.82x |
| Weeks tracked | 4 |
| Average week | -0.04% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.3% | +3 |
| BTC perp | +16.9% | +2 |
| BCH perp | +16.1% | +5 |
| SOL perp | +15.3% | +3 |
| BNB perp | +15.0% | +2 |
| DOT perp | +14.9% | +14 |
| XLM perp | +11.3% | +1 |
| ADA perp | +10.2% | +4 |
| ZEC perp | +8.9% | +1 |
| AVAX perp | +8.6% | +10 |
| XRP perp | +8.2% | +1 |
| ETH perp | +8.2% | +3 |
| LINK perp | +6.5% | +1 |
| DOGE perp | +5.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -10.9% | -1 |
| LTC perp | -5.8% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
