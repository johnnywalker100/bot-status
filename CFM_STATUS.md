# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9089** (-9.11% since start) |
| Peak / drawdown | 1.0141 / -10.38% |
| Ticks recorded | 573 |
| Last tick | 2026-08-17T02:08:39.588472+00:00 (-0.0273%) |
| Risk rails | normal (dd -10.4%) |
| Data source | coinbase-cfm (bar 2026-08-17 01:00:00+00:00) |
| Gross leverage | 2.99x |
| Weeks tracked | 4 |
| Average week | -0.41% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +17.4% | +9 |
| XLM perp | +17.2% | +2 |
| ETH perp | +14.5% | +7 |
| AVAX perp | +7.0% | +10 |
| BCH perp | +6.7% | +3 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -48.5% | -7 |
| DOGE perp | -46.2% | -12 |
| LTC perp | -38.9% | -16 |
| NEAR perp | -35.4% | -4 |
| LINK perp | -20.8% | -4 |
| DOT perp | -11.7% | -14 |
| XRP perp | -11.0% | -2 |
| ZEC perp | -10.8% | -2 |
| SOL perp | -8.3% | -2 |
| AAVE perp | -4.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
