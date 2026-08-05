# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9190** (-8.10% since start) |
| Peak / drawdown | 1.0141 / -9.37% |
| Ticks recorded | 297 |
| Last tick | 2026-08-05T12:10:15.205702+00:00 (-0.1455%) |
| Risk rails | normal (dd -9.4%) |
| Data source | coinbase-cfm (bar 2026-08-05 11:00:00+00:00) |
| Gross leverage | 3.11x |
| Weeks tracked | 2 |
| Average week | -0.27% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.27% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.6% | +17 |
| XLM perp | +27.3% | +3 |
| AAVE perp | +19.8% | +4 |
| SOL perp | +16.1% | +4 |
| ADA perp | +14.8% | +7 |
| BTC perp | +7.0% | +1 |
| AVAX perp | +4.4% | +6 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.2% | -9 |
| BCH perp | -23.3% | -10 |
| XRP perp | -23.1% | -4 |
| ZEC perp | -22.6% | -4 |
| LTC perp | -21.9% | -9 |
| BNB perp | -19.5% | -3 |
| LINK perp | -17.8% | -4 |
| DOT perp | -15.7% | -17 |
| NEAR perp | -9.2% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
