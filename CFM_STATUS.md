# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8991** (-10.09% since start) |
| Peak / drawdown | 1.0141 / -11.34% |
| Ticks recorded | 581 |
| Last tick | 2026-08-17T10:09:14.867810+00:00 (-0.1270%) |
| Risk rails | normal (dd -11.3%) |
| Data source | coinbase-cfm (bar 2026-08-17 09:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 4 |
| Average week | -0.68% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.77% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +17.5% | +2 |
| ADA perp | +17.4% | +9 |
| ETH perp | +14.7% | +7 |
| AVAX perp | +7.0% | +10 |
| BCH perp | +4.5% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BTC perp | -49.2% | -7 |
| DOGE perp | -46.9% | -12 |
| LTC perp | -39.1% | -16 |
| NEAR perp | -36.4% | -4 |
| LINK perp | -20.9% | -4 |
| DOT perp | -11.8% | -14 |
| ZEC perp | -11.3% | -2 |
| XRP perp | -11.1% | -2 |
| SOL perp | -8.4% | -2 |
| AAVE perp | -4.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
