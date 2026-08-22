# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9449** (-5.51% since start) |
| Peak / drawdown | 1.0141 / -6.82% |
| Ticks recorded | 693 |
| Last tick | 2026-08-22T03:10:11.455573+00:00 (+2.4189%) |
| Risk rails | normal (dd -6.8%) |
| Data source | coinbase-cfm (bar 2026-08-22 02:00:00+00:00) |
| Gross leverage | 1.45x |
| Weeks tracked | 4 |
| Average week | +0.57% |
| Weeks >= +3% | 25% |
| Best / worst week | +3.24% / -1.45% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.2% | +3 |
| BCH perp | +12.8% | +4 |
| DOT perp | +11.6% | +11 |
| XLM perp | +11.1% | +1 |
| SOL perp | +10.2% | +2 |
| ZEC perp | +8.8% | +1 |
| BTC perp | +8.3% | +1 |
| XRP perp | +8.2% | +1 |
| ETH perp | +8.0% | +3 |
| ADA perp | +7.7% | +3 |
| BNB perp | +7.6% | +1 |
| AVAX perp | +7.0% | +8 |
| LINK perp | +6.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -11.1% | -1 |
| LTC perp | -5.7% | -2 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
