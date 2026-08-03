# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9538** (-4.62% since start) |
| Peak / drawdown | 1.0141 / -5.95% |
| Ticks recorded | 249 |
| Last tick | 2026-08-03T12:12:05.433869+00:00 (+0.0786%) |
| Risk rails | normal (dd -5.9%) |
| Data source | coinbase-cfm (bar 2026-08-03 11:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 2 |
| Average week | +1.58% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +1.42% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.8% | +16 |
| XLM perp | +27.0% | +3 |
| SOL perp | +15.2% | +4 |
| ADA perp | +9.8% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +3.4% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -39.2% | -17 |
| BNB perp | -36.8% | -6 |
| DOGE perp | -32.8% | -9 |
| BCH perp | -24.2% | -11 |
| ZEC perp | -20.3% | -4 |
| LINK perp | -17.1% | -4 |
| XRP perp | -16.7% | -3 |
| BTC perp | -13.1% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -3.4% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
