# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9465** (-5.35% since start) |
| Peak / drawdown | 1.0141 / -6.67% |
| Ticks recorded | 1622 |
| Last tick | 2026-09-30T02:08:25.281529+00:00 (+0.0701%) |
| Risk rails | normal (dd -6.7%) |
| Data source | coinbase-cfm (bar 2026-09-30 01:00:00+00:00) |
| Gross leverage | 0.81x |
| Weeks tracked | 10 |
| Average week | +0.28% |
| Weeks >= +3% | 20% |
| Best / worst week | +5.83% / -2.88% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ZEC perp | +15.1% | +1 |
| ETH perp | +11.3% | +4 |
| BTC perp | +8.8% | +1 |
| AAVE perp | +8.5% | +1 |
| DOT perp | +7.7% | +6 |
| BCH perp | +6.5% | +2 |
| SOL perp | +6.3% | +1 |
| AVAX perp | +6.0% | +5 |
| LTC perp | +3.6% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -5.0% | -1 |
| ADA perp | -2.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
