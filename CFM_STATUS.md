# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9328** (-6.72% since start) |
| Peak / drawdown | 1.0141 / -8.02% |
| Ticks recorded | 167 |
| Last tick | 2026-07-31T01:08:53.907215+00:00 (-0.3984%) |
| Risk rails | normal (dd -7.9%) |
| Data source | coinbase-cfm (bar 2026-07-31 00:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +0.91% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.91% / +0.91% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +21.4% | +4 |
| ADA perp | +20.1% | +11 |
| XLM perp | +18.4% | +2 |
| DOT perp | +10.7% | +13 |
| ETH perp | +10.3% | +5 |
| SOL perp | +8.0% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.2% | -13 |
| LTC perp | -39.2% | -16 |
| BCH perp | -25.6% | -11 |
| BNB perp | -25.4% | -4 |
| LINK perp | -18.2% | -4 |
| ZEC perp | -15.2% | -3 |
| BTC perp | -13.9% | -2 |
| AVAX perp | -10.4% | -15 |
| NEAR perp | -9.0% | -1 |
| XRP perp | -5.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
