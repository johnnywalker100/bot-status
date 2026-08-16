# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9096** (-9.04% since start) |
| Peak / drawdown | 1.0141 / -10.31% |
| Ticks recorded | 566 |
| Last tick | 2026-08-16T19:09:00.486484+00:00 (-0.0949%) |
| Risk rails | normal (dd -10.3%) |
| Data source | coinbase-cfm (bar 2026-08-16 18:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 3 |
| Average week | -0.52% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.06% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.8% | +5 |
| XLM perp | +17.3% | +2 |
| ETH perp | +16.6% | +8 |
| SOL perp | +12.4% | +3 |
| AVAX perp | +7.0% | +10 |
| BCH perp | +4.5% | +2 |
| ADA perp | +1.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -48.6% | -7 |
| DOGE perp | -38.5% | -10 |
| NEAR perp | -35.4% | -4 |
| LTC perp | -34.2% | -14 |
| LINK perp | -20.7% | -4 |
| ZEC perp | -16.2% | -3 |
| DOT perp | -11.8% | -14 |
| BNB perp | -6.7% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
