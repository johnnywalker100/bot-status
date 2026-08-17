# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9157** (-8.43% since start) |
| Peak / drawdown | 1.0141 / -9.70% |
| Ticks recorded | 571 |
| Last tick | 2026-08-17T00:14:26.320829+00:00 (+0.0532%) |
| Risk rails | normal (dd -9.7%) |
| Data source | coinbase-cfm (bar 2026-08-16 23:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 4 |
| Average week | -0.23% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.4% | +5 |
| XLM perp | +17.1% | +2 |
| ETH perp | +16.4% | +8 |
| SOL perp | +12.2% | +3 |
| AVAX perp | +6.9% | +10 |
| BCH perp | +6.7% | +3 |
| ADA perp | +1.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -48.0% | -7 |
| DOGE perp | -38.0% | -10 |
| NEAR perp | -35.0% | -4 |
| LTC perp | -33.7% | -14 |
| LINK perp | -20.5% | -4 |
| ZEC perp | -15.9% | -3 |
| DOT perp | -11.6% | -14 |
| BNB perp | -6.6% | -1 |
| XRP perp | -5.4% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
