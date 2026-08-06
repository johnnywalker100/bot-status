# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9273** (-7.27% since start) |
| Peak / drawdown | 1.0141 / -8.56% |
| Ticks recorded | 320 |
| Last tick | 2026-08-06T11:08:50.565820+00:00 (+0.5168%) |
| Risk rails | normal (dd -8.6%) |
| Data source | coinbase-cfm (bar 2026-08-06 10:00:00+00:00) |
| Gross leverage | 2.79x |
| Weeks tracked | 2 |
| Average week | +0.17% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.39% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.8% | +17 |
| XLM perp | +25.9% | +3 |
| AAVE perp | +18.9% | +4 |
| ADA perp | +10.2% | +5 |
| SOL perp | +7.9% | +2 |
| LTC perp | +7.2% | +3 |
| BTC perp | +7.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -37.2% | -10 |
| BCH perp | -36.4% | -16 |
| NEAR perp | -27.2% | -3 |
| ZEC perp | -21.3% | -4 |
| BNB perp | -19.2% | -3 |
| DOT perp | -14.2% | -16 |
| XRP perp | -5.6% | -1 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
