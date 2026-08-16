# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9121** (-8.79% since start) |
| Peak / drawdown | 1.0141 / -10.06% |
| Ticks recorded | 552 |
| Last tick | 2026-08-16T05:11:59.421436+00:00 (-0.1198%) |
| Risk rails | normal (dd -10.1%) |
| Data source | coinbase-cfm (bar 2026-08-16 04:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 3 |
| Average week | -0.43% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.79% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.6% | +5 |
| XLM perp | +17.2% | +2 |
| ETH perp | +16.5% | +8 |
| SOL perp | +12.4% | +3 |
| AVAX perp | +7.0% | +10 |
| BCH perp | +4.5% | +2 |
| ADA perp | +1.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -48.4% | -7 |
| DOGE perp | -38.2% | -10 |
| NEAR perp | -35.4% | -4 |
| LTC perp | -33.9% | -14 |
| LINK perp | -20.6% | -4 |
| ZEC perp | -16.1% | -3 |
| DOT perp | -11.6% | -14 |
| BNB perp | -6.6% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
