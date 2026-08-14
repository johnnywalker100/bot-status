# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9333** (-6.67% since start) |
| Peak / drawdown | 1.0141 / -7.97% |
| Ticks recorded | 520 |
| Last tick | 2026-08-14T20:09:09.332129+00:00 (-0.8924%) |
| Risk rails | normal (dd -8.0%) |
| Data source | coinbase-cfm (bar 2026-08-14 19:00:00+00:00) |
| Gross leverage | 3.05x |
| Weeks tracked | 3 |
| Average week | +0.33% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +25.6% | +3 |
| AAVE perp | +23.0% | +5 |
| ETH perp | +10.1% | +5 |
| AVAX perp | +9.6% | +14 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -33.7% | -5 |
| DOGE perp | -33.6% | -9 |
| BNB perp | -32.5% | -5 |
| NEAR perp | -25.9% | -3 |
| LINK perp | -24.0% | -5 |
| BCH perp | -21.8% | -10 |
| ADA perp | -17.3% | -9 |
| ZEC perp | -15.8% | -3 |
| LTC perp | -14.0% | -6 |
| DOT perp | -8.1% | -10 |
| XRP perp | -5.3% | -1 |
| SOL perp | -4.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
