# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9131** (-8.69% since start) |
| Peak / drawdown | 1.0141 / -9.96% |
| Ticks recorded | 531 |
| Last tick | 2026-08-15T08:08:35.319769+00:00 (+0.2142%) |
| Risk rails | normal (dd -10.0%) |
| Data source | coinbase-cfm (bar 2026-08-15 07:00:00+00:00) |
| Gross leverage | 2.96x |
| Weeks tracked | 3 |
| Average week | -0.40% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.69% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.4% | +6 |
| XLM perp | +17.3% | +2 |
| AVAX perp | +8.0% | +11 |
| BCH perp | +6.8% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.3% | -10 |
| NEAR perp | -35.9% | -4 |
| BTC perp | -34.5% | -5 |
| LTC perp | -33.7% | -14 |
| BNB perp | -26.8% | -4 |
| LINK perp | -25.5% | -5 |
| ZEC perp | -10.7% | -2 |
| ADA perp | -9.8% | -5 |
| DOT perp | -8.4% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
