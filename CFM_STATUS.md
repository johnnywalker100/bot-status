# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9251** (-7.49% since start) |
| Peak / drawdown | 1.0141 / -8.78% |
| Ticks recorded | 420 |
| Last tick | 2026-08-10T16:08:53.493238+00:00 (-0.2195%) |
| Risk rails | normal (dd -8.8%) |
| Data source | coinbase-cfm (bar 2026-08-10 15:00:00+00:00) |
| Gross leverage | 2.22x |
| Weeks tracked | 3 |
| Average week | +0.03% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.4% | +14 |
| AAVE perp | +19.4% | +4 |
| LTC perp | +12.2% | +5 |
| XLM perp | +8.8% | +1 |
| BTC perp | +6.9% | +1 |
| AVAX perp | +5.6% | +8 |
| ADA perp | +4.2% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -49.0% | -13 |
| BCH perp | -25.5% | -11 |
| ZEC perp | -21.8% | -4 |
| BNB perp | -19.5% | -3 |
| LINK perp | -9.0% | -2 |
| NEAR perp | -8.8% | -1 |
| DOT perp | -2.6% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
