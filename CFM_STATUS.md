# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9546** (-4.54% since start) |
| Peak / drawdown | 1.0141 / -5.87% |
| Ticks recorded | 190 |
| Last tick | 2026-08-01T01:08:43.087801+00:00 (-0.4692%) |
| Risk rails | normal (dd -5.8%) |
| Data source | coinbase-cfm (bar 2026-08-01 00:00:00+00:00) |
| Gross leverage | 3.05x |
| Weeks tracked | 1 |
| Average week | +3.27% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.27% / +3.27% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.2% | +4 |
| XLM perp | +18.0% | +2 |
| ETH perp | +15.6% | +8 |
| DOT perp | +14.3% | +18 |
| ADA perp | +14.2% | +8 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.2% | -14 |
| BNB perp | -30.8% | -5 |
| LTC perp | -30.1% | -13 |
| BCH perp | -28.5% | -13 |
| ZEC perp | -24.0% | -5 |
| LINK perp | -17.1% | -4 |
| BTC perp | -13.2% | -2 |
| NEAR perp | -8.7% | -1 |
| SOL perp | -7.6% | -2 |
| AVAX perp | -6.7% | -10 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
