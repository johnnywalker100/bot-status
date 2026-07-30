# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9475** (-5.25% since start) |
| Peak / drawdown | 1.0141 / -6.57% |
| Ticks recorded | 146 |
| Last tick | 2026-07-30T04:08:31.166727+00:00 (+0.3051%) |
| Risk rails | normal (dd -6.6%) |
| Data source | coinbase-cfm (bar 2026-07-30 03:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 1 |
| Average week | +2.50% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.50% / +2.50% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +22.2% | +13 |
| AAVE perp | +20.2% | +4 |
| ETH perp | +16.1% | +8 |
| DOT perp | +13.7% | +17 |
| XLM perp | +9.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.4% | -12 |
| LTC perp | -40.6% | -17 |
| BNB perp | -30.2% | -5 |
| NEAR perp | -25.8% | -3 |
| ZEC perp | -24.9% | -5 |
| LINK perp | -17.6% | -4 |
| BTC perp | -13.5% | -2 |
| BCH perp | -8.9% | -4 |
| AVAX perp | -7.5% | -11 |
| XRP perp | -5.7% | -1 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
