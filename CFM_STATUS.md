# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8930** (-10.70% since start) |
| Peak / drawdown | 1.0141 / -11.94% |
| Ticks recorded | 1085 |
| Last tick | 2026-09-07T13:08:20.637586+00:00 (+0.5420%) |
| Risk rails | normal (dd -11.9%) |
| Data source | coinbase-cfm (bar 2026-09-07 12:00:00+00:00) |
| Gross leverage | 0.81x |
| Weeks tracked | 7 |
| Average week | -0.48% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| SOL perp | +11.8% | +2 |
| AVAX perp | +10.9% | +12 |
| BTC perp | +8.9% | +1 |
| BNB perp | +8.4% | +1 |
| XRP perp | +7.9% | +1 |
| AAVE perp | +7.5% | +1 |
| DOT perp | +5.7% | +5 |
| ETH perp | +5.6% | +2 |
| DOGE perp | +5.1% | +1 |
| LTC perp | +3.3% | +1 |
| BCH perp | +2.9% | +1 |
| ADA perp | +2.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| (none) | | |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
