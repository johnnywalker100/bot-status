# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8946** (-10.54% since start) |
| Peak / drawdown | 1.0141 / -11.79% |
| Ticks recorded | 578 |
| Last tick | 2026-08-17T07:08:30.562443+00:00 (-0.7233%) |
| Risk rails | normal (dd -11.8%) |
| Data source | coinbase-cfm (bar 2026-08-17 06:00:00+00:00) |
| Gross leverage | 2.93x |
| Weeks tracked | 4 |
| Average week | -0.80% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.26% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +17.8% | +9 |
| XLM perp | +17.7% | +2 |
| ETH perp | +12.8% | +6 |
| AVAX perp | +7.1% | +10 |
| BCH perp | +4.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -49.7% | -7 |
| DOGE perp | -47.2% | -12 |
| LTC perp | -39.5% | -16 |
| NEAR perp | -27.5% | -3 |
| LINK perp | -21.2% | -4 |
| DOT perp | -11.9% | -14 |
| ZEC perp | -11.5% | -2 |
| XRP perp | -11.2% | -2 |
| SOL perp | -8.5% | -2 |
| AAVE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
