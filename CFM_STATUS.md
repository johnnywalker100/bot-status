# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9062** (-9.38% since start) |
| Peak / drawdown | 1.0141 / -10.64% |
| Ticks recorded | 545 |
| Last tick | 2026-08-15T22:09:30.396077+00:00 (-0.0625%) |
| Risk rails | normal (dd -10.6%) |
| Data source | coinbase-cfm (bar 2026-08-15 21:00:00+00:00) |
| Gross leverage | 2.88x |
| Weeks tracked | 3 |
| Average week | -0.64% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.43% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.9% | +5 |
| XLM perp | +17.5% | +2 |
| AVAX perp | +7.2% | +10 |
| BCH perp | +6.7% | +3 |
| ETH perp | +2.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.6% | -10 |
| NEAR perp | -36.1% | -4 |
| BTC perp | -34.8% | -5 |
| LTC perp | -34.0% | -14 |
| BNB perp | -26.9% | -4 |
| LINK perp | -21.1% | -4 |
| ZEC perp | -10.8% | -2 |
| ADA perp | -9.8% | -5 |
| DOT perp | -8.5% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
