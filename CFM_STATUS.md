# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9487** (-5.13% since start) |
| Peak / drawdown | 1.0141 / -6.45% |
| Ticks recorded | 151 |
| Last tick | 2026-07-30T09:08:32.997550+00:00 (-0.3014%) |
| Risk rails | normal (dd -6.4%) |
| Data source | coinbase-cfm (bar 2026-07-30 08:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 1 |
| Average week | +2.64% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.64% / +2.64% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.6% | +13 |
| AAVE perp | +20.6% | +4 |
| ETH perp | +16.1% | +8 |
| DOT perp | +13.8% | +17 |
| XLM perp | +9.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.3% | -12 |
| LTC perp | -40.6% | -17 |
| NEAR perp | -25.8% | -3 |
| ZEC perp | -25.1% | -5 |
| BNB perp | -24.4% | -4 |
| BTC perp | -20.3% | -3 |
| LINK perp | -17.5% | -4 |
| BCH perp | -8.9% | -4 |
| AVAX perp | -7.5% | -11 |
| XRP perp | -5.7% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
