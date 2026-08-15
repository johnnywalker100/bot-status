# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9066** (-9.34% since start) |
| Peak / drawdown | 1.0141 / -10.60% |
| Ticks recorded | 540 |
| Last tick | 2026-08-15T17:08:52.458493+00:00 (+0.0459%) |
| Risk rails | normal (dd -10.6%) |
| Data source | coinbase-cfm (bar 2026-08-15 16:00:00+00:00) |
| Gross leverage | 2.93x |
| Weeks tracked | 3 |
| Average week | -0.63% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.39% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.8% | +6 |
| XLM perp | +17.6% | +2 |
| AVAX perp | +7.9% | +11 |
| BCH perp | +6.8% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.6% | -10 |
| NEAR perp | -36.2% | -4 |
| BTC perp | -34.8% | -5 |
| LTC perp | -34.0% | -14 |
| BNB perp | -27.0% | -4 |
| LINK perp | -21.1% | -4 |
| ZEC perp | -10.8% | -2 |
| ADA perp | -9.8% | -5 |
| DOT perp | -7.7% | -9 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
