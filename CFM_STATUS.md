# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9096** (-9.04% since start) |
| Peak / drawdown | 1.0141 / -10.30% |
| Ticks recorded | 313 |
| Last tick | 2026-08-06T04:08:35.127814+00:00 (-0.8062%) |
| Risk rails | normal (dd -10.3%) |
| Data source | coinbase-cfm (bar 2026-08-06 03:00:00+00:00) |
| Gross leverage | 2.83x |
| Weeks tracked | 2 |
| Average week | -0.77% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -3.27% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +35.4% | +17 |
| XLM perp | +26.7% | +3 |
| AAVE perp | +19.4% | +4 |
| ADA perp | +10.3% | +5 |
| SOL perp | +8.1% | +2 |
| LTC perp | +7.4% | +3 |
| BTC perp | +7.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.2% | -10 |
| BCH perp | -37.7% | -16 |
| ZEC perp | -22.4% | -4 |
| BNB perp | -19.6% | -3 |
| NEAR perp | -18.9% | -2 |
| DOT perp | -13.9% | -15 |
| XRP perp | -11.5% | -2 |
| LINK perp | -4.5% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
