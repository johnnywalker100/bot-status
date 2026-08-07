# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9423** (-5.77% since start) |
| Peak / drawdown | 1.0141 / -7.09% |
| Ticks recorded | 354 |
| Last tick | 2026-08-07T22:08:24.070706+00:00 (+1.1320%) |
| Risk rails | normal (dd -7.1%) |
| Data source | coinbase-cfm (bar 2026-08-07 21:00:00+00:00) |
| Gross leverage | 2.54x |
| Weeks tracked | 2 |
| Average week | +0.97% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.5% | +14 |
| ADA perp | +21.4% | +10 |
| XLM perp | +8.6% | +1 |
| SOL perp | +7.8% | +2 |
| XRP perp | +5.4% | +1 |
| AAVE perp | +4.7% | +1 |
| LTC perp | +2.4% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -45.0% | -20 |
| BNB perp | -37.7% | -6 |
| DOGE perp | -37.0% | -10 |
| ZEC perp | -16.2% | -3 |
| LINK perp | -13.0% | -3 |
| DOT perp | -12.9% | -15 |
| NEAR perp | -8.4% | -1 |
| AVAX perp | -5.5% | -8 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
