# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9553** (-4.47% since start) |
| Peak / drawdown | 1.0141 / -5.80% |
| Ticks recorded | 250 |
| Last tick | 2026-08-03T13:11:22.929181+00:00 (+0.1574%) |
| Risk rails | normal (dd -5.8%) |
| Data source | coinbase-cfm (bar 2026-08-03 12:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 2 |
| Average week | +1.66% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +1.58% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +30.9% | +16 |
| XLM perp | +26.9% | +3 |
| SOL perp | +15.1% | +4 |
| ADA perp | +9.9% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +3.4% | +4 |

| Short | Size | Contracts |
|---|---|---|
| LTC perp | -39.1% | -17 |
| BNB perp | -36.8% | -6 |
| DOGE perp | -32.7% | -9 |
| BCH perp | -24.2% | -11 |
| ZEC perp | -20.2% | -4 |
| LINK perp | -17.1% | -4 |
| XRP perp | -16.7% | -3 |
| BTC perp | -13.1% | -2 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -3.4% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
