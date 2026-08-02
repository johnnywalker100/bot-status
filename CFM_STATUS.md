# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9332** (-6.68% since start) |
| Peak / drawdown | 1.0141 / -7.98% |
| Ticks recorded | 235 |
| Last tick | 2026-08-02T22:08:50.349576+00:00 (-0.4239%) |
| Risk rails | normal (dd -8.0%) |
| Data source | coinbase-cfm (bar 2026-08-02 21:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +0.96% |
| Weeks >= +3% | 0% |
| Best / worst week | +0.96% / +0.96% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +28.2% | +3 |
| ETH perp | +16.2% | +8 |
| ADA perp | +14.2% | +7 |
| DOT perp | +11.9% | +14 |
| AAVE perp | +5.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -41.8% | -11 |
| BNB perp | -37.9% | -6 |
| LTC perp | -26.5% | -11 |
| BCH perp | -25.3% | -11 |
| LINK perp | -22.5% | -5 |
| ZEC perp | -21.1% | -4 |
| BTC perp | -13.6% | -2 |
| XRP perp | -11.7% | -2 |
| NEAR perp | -9.2% | -1 |
| AVAX perp | -8.5% | -12 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
