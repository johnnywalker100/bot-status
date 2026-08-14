# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9244** (-7.56% since start) |
| Peak / drawdown | 1.0141 / -8.85% |
| Ticks recorded | 502 |
| Last tick | 2026-08-14T02:09:47.141437+00:00 (-0.1550%) |
| Risk rails | normal (dd -8.8%) |
| Data source | coinbase-cfm (bar 2026-08-14 01:00:00+00:00) |
| Gross leverage | 3.05x |
| Weeks tracked | 3 |
| Average week | +0.01% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.9% | +3 |
| AAVE perp | +23.9% | +5 |
| ETH perp | +10.2% | +5 |
| AVAX perp | +9.8% | +14 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -34.4% | -5 |
| DOGE perp | -34.2% | -9 |
| BNB perp | -33.1% | -5 |
| NEAR perp | -26.3% | -3 |
| LINK perp | -24.0% | -5 |
| BCH perp | -22.4% | -10 |
| ADA perp | -17.8% | -9 |
| LTC perp | -14.5% | -6 |
| ZEC perp | -10.6% | -2 |
| DOT perp | -8.3% | -10 |
| XRP perp | -5.5% | -1 |
| SOL perp | -4.1% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
