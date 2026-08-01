# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9634** (-3.66% since start) |
| Peak / drawdown | 1.0141 / -5.01% |
| Ticks recorded | 202 |
| Last tick | 2026-08-01T13:08:26.497078+00:00 (+0.0962%) |
| Risk rails | normal (dd -5.0%) |
| Data source | coinbase-cfm (bar 2026-08-01 12:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +4.22% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.22% / +4.22% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +18.9% | +4 |
| XLM perp | +17.8% | +2 |
| ETH perp | +15.5% | +8 |
| ADA perp | +14.5% | +8 |
| DOT perp | +14.4% | +18 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.8% | -14 |
| BNB perp | -30.0% | -5 |
| LTC perp | -29.9% | -13 |
| BCH perp | -28.1% | -13 |
| ZEC perp | -24.2% | -5 |
| LINK perp | -16.8% | -4 |
| BTC perp | -13.1% | -2 |
| NEAR perp | -8.7% | -1 |
| SOL perp | -7.6% | -2 |
| AVAX perp | -6.6% | -10 |
| XRP perp | -5.5% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
