# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9025** (-9.75% since start) |
| Peak / drawdown | 1.0141 / -11.00% |
| Ticks recorded | 716 |
| Last tick | 2026-08-23T02:08:24.140949+00:00 (-0.5931%) |
| Risk rails | normal (dd -11.0%) |
| Data source | coinbase-cfm (bar 2026-08-23 01:00:00+00:00) |
| Gross leverage | 0.86x |
| Weeks tracked | 4 |
| Average week | -0.59% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +13.9% | +2 |
| XLM perp | +10.9% | +1 |
| BCH perp | +9.2% | +3 |
| BTC perp | +8.5% | +1 |
| BNB perp | +7.7% | +1 |
| DOT perp | +7.1% | +7 |
| LINK perp | +6.4% | +1 |
| ETH perp | +5.4% | +2 |
| SOL perp | +5.3% | +1 |
| ADA perp | +5.0% | +2 |
| AVAX perp | +4.1% | +5 |
| LTC perp | +2.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
