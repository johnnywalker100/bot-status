# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9073** (-9.27% since start) |
| Peak / drawdown | 1.0141 / -10.54% |
| Ticks recorded | 563 |
| Last tick | 2026-08-16T16:10:27.803209+00:00 (-0.2470%) |
| Risk rails | normal (dd -10.5%) |
| Data source | coinbase-cfm (bar 2026-08-16 15:00:00+00:00) |
| Gross leverage | 3.00x |
| Weeks tracked | 3 |
| Average week | -0.61% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.31% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +23.9% | +5 |
| XLM perp | +17.4% | +2 |
| ETH perp | +16.6% | +8 |
| SOL perp | +12.5% | +3 |
| AVAX perp | +7.1% | +10 |
| BCH perp | +4.5% | +2 |
| ADA perp | +1.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -48.7% | -7 |
| DOGE perp | -38.6% | -10 |
| NEAR perp | -35.8% | -4 |
| LTC perp | -32.0% | -13 |
| LINK perp | -20.7% | -4 |
| ZEC perp | -16.3% | -3 |
| DOT perp | -11.8% | -14 |
| BNB perp | -6.7% | -1 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
