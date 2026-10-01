# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9373** (-6.27% since start) |
| Peak / drawdown | 1.0141 / -7.58% |
| Ticks recorded | 1659 |
| Last tick | 2026-10-01T15:08:35.295397+00:00 (-0.4784%) |
| Risk rails | normal (dd -7.6%) |
| Data source | coinbase-cfm (bar 2026-10-01 14:00:00+00:00) |
| Gross leverage | 0.75x |
| Weeks tracked | 10 |
| Average week | +0.18% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +14.7% | +1 |
| ETH perp | +11.5% | +4 |
| BTC perp | +9.0% | +1 |
| AAVE perp | +8.8% | +1 |
| SOL perp | +6.2% | +1 |
| AVAX perp | +5.8% | +5 |
| DOT perp | +5.0% | +4 |
| LTC perp | +3.6% | +1 |
| BCH perp | +3.3% | +1 |
| ADA perp | +2.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
