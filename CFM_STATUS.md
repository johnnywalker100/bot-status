# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9499** (-5.01% since start) |
| Peak / drawdown | 1.0141 / -6.33% |
| Ticks recorded | 173 |
| Last tick | 2026-07-31T07:08:30.125951+00:00 (+0.1609%) |
| Risk rails | normal (dd -6.3%) |
| Data source | coinbase-cfm (bar 2026-07-31 06:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +2.76% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.76% / +2.76% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.2% | +12 |
| AAVE perp | +20.7% | +4 |
| XLM perp | +17.9% | +2 |
| DOT perp | +10.5% | +13 |
| ETH perp | +10.0% | +5 |
| SOL perp | +7.8% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.5% | -14 |
| LTC perp | -38.0% | -16 |
| BNB perp | -24.9% | -4 |
| BCH perp | -24.7% | -11 |
| ZEC perp | -19.3% | -4 |
| LINK perp | -17.5% | -4 |
| BTC perp | -13.5% | -2 |
| AVAX perp | -10.1% | -15 |
| NEAR perp | -8.7% | -1 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
