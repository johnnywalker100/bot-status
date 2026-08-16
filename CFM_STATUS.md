# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9095** (-9.05% since start) |
| Peak / drawdown | 1.0141 / -10.31% |
| Ticks recorded | 562 |
| Last tick | 2026-08-16T15:08:54.900578+00:00 (-0.0857%) |
| Risk rails | normal (dd -10.3%) |
| Data source | coinbase-cfm (bar 2026-08-16 14:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 3 |
| Average week | -0.52% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.07% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.8% | +5 |
| XLM perp | +17.3% | +2 |
| ETH perp | +16.6% | +8 |
| SOL perp | +12.4% | +3 |
| AVAX perp | +7.1% | +10 |
| BCH perp | +4.5% | +2 |
| ADA perp | +1.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -48.5% | -7 |
| DOGE perp | -38.5% | -10 |
| NEAR perp | -35.6% | -4 |
| LTC perp | -34.1% | -14 |
| LINK perp | -20.6% | -4 |
| ZEC perp | -16.3% | -3 |
| DOT perp | -11.8% | -14 |
| BNB perp | -6.7% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
