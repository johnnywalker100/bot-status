# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9293** (-7.07% since start) |
| Peak / drawdown | 1.0141 / -8.36% |
| Ticks recorded | 421 |
| Last tick | 2026-08-10T17:08:56.397936+00:00 (+0.4606%) |
| Risk rails | normal (dd -8.4%) |
| Data source | coinbase-cfm (bar 2026-08-10 16:00:00+00:00) |
| Gross leverage | 2.20x |
| Weeks tracked | 3 |
| Average week | +0.19% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.24% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +28.2% | +14 |
| AAVE perp | +19.2% | +4 |
| LTC perp | +12.1% | +5 |
| XLM perp | +8.7% | +1 |
| BTC perp | +6.9% | +1 |
| AVAX perp | +5.6% | +8 |
| ADA perp | +4.2% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -48.7% | -13 |
| BCH perp | -25.2% | -11 |
| ZEC perp | -21.3% | -4 |
| BNB perp | -19.3% | -3 |
| LINK perp | -8.9% | -2 |
| NEAR perp | -8.6% | -1 |
| DOT perp | -2.6% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
