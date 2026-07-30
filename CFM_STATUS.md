# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9453** (-5.47% since start) |
| Peak / drawdown | 1.0141 / -6.79% |
| Ticks recorded | 144 |
| Last tick | 2026-07-30T02:08:34.302586+00:00 (-0.5626%) |
| Risk rails | normal (dd -6.8%) |
| Data source | coinbase-cfm (bar 2026-07-30 01:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 1 |
| Average week | +2.27% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.27% / +2.27% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.5% | +13 |
| AAVE perp | +20.4% | +4 |
| ETH perp | +16.2% | +8 |
| DOT perp | +13.8% | +17 |
| XLM perp | +9.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.8% | -12 |
| LTC perp | -38.4% | -16 |
| BNB perp | -30.5% | -5 |
| NEAR perp | -25.8% | -3 |
| ZEC perp | -24.9% | -5 |
| LINK perp | -17.7% | -4 |
| BTC perp | -13.6% | -2 |
| BCH perp | -8.9% | -4 |
| AVAX perp | -7.6% | -11 |
| XRP perp | -5.7% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
