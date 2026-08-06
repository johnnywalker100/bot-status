# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9129** (-8.71% since start) |
| Peak / drawdown | 1.0141 / -9.98% |
| Ticks recorded | 315 |
| Last tick | 2026-08-06T06:09:17.594493+00:00 (+0.5130%) |
| Risk rails | normal (dd -10.0%) |
| Data source | coinbase-cfm (bar 2026-08-06 05:00:00+00:00) |
| Gross leverage | 2.82x |
| Weeks tracked | 2 |
| Average week | -0.59% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.93% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +33.5% | +16 |
| XLM perp | +26.7% | +3 |
| AAVE perp | +19.5% | +4 |
| ADA perp | +10.3% | +5 |
| SOL perp | +8.1% | +2 |
| LTC perp | +7.4% | +3 |
| BTC perp | +7.1% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -38.3% | -10 |
| BCH perp | -37.6% | -16 |
| ZEC perp | -22.3% | -4 |
| BNB perp | -19.6% | -3 |
| NEAR perp | -18.9% | -2 |
| DOT perp | -14.7% | -16 |
| XRP perp | -11.5% | -2 |
| LINK perp | -4.5% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
