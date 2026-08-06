# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9122** (-8.78% since start) |
| Peak / drawdown | 1.0141 / -10.05% |
| Ticks recorded | 316 |
| Last tick | 2026-08-06T07:08:37.044581+00:00 (-0.0775%) |
| Risk rails | normal (dd -10.1%) |
| Data source | coinbase-cfm (bar 2026-08-06 06:00:00+00:00) |
| Gross leverage | 2.82x |
| Weeks tracked | 2 |
| Average week | -0.63% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.00% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.5% | +16 |
| XLM perp | +26.7% | +3 |
| AAVE perp | +19.4% | +4 |
| ADA perp | +10.3% | +5 |
| SOL perp | +8.1% | +2 |
| LTC perp | +7.4% | +3 |
| BTC perp | +7.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.3% | -10 |
| BCH perp | -37.7% | -16 |
| ZEC perp | -22.3% | -4 |
| BNB perp | -19.6% | -3 |
| NEAR perp | -18.8% | -2 |
| DOT perp | -14.6% | -16 |
| XRP perp | -11.5% | -2 |
| LINK perp | -4.5% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
