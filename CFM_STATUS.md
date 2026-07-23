# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9964** (-0.36% since start) |
| Peak / drawdown | 1.0000 / -0.36% |
| Ticks recorded | 2 |
| Last tick | 2026-07-23T23:46:06.155719+00:00 (-0.0737%) |
| Risk rails | normal (dd -0.3%) |
| Data source | coinbase-cfm (bar 2026-07-23 22:00:00+00:00) |
| Gross leverage | 2.46x |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +28.7% | +6 |
| ETH perp | +15.1% | +8 |
| BCH perp | +14.9% | +7 |
| ADA perp | +11.8% | +7 |
| HYPE perp | +11.6% | +2 |
| HBAR perp | +10.7% | +3 |
| SOL perp | +7.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -31.3% | -9 |
| SUI perp | -26.2% | -7 |
| LTC perp | -21.2% | -9 |
| BNB perp | -17.1% | -3 |
| SHIB perp | -16.2% | -39 |
| NEAR perp | -9.4% | -1 |
| ENA perp | -8.9% | -2 |
| BTC perp | -6.5% | -1 |
| LINK perp | -4.3% | -1 |
| PEPE perp | -2.8% | -1 |
| AVAX perp | -1.3% | -2 |
| DOT perp | -0.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
