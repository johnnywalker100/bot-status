# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9226** (-7.74% since start) |
| Peak / drawdown | 1.0141 / -9.03% |
| Ticks recorded | 319 |
| Last tick | 2026-08-06T10:09:13.237030+00:00 (+0.5910%) |
| Risk rails | normal (dd -9.0%) |
| Data source | coinbase-cfm (bar 2026-08-06 09:00:00+00:00) |
| Gross leverage | 2.81x |
| Weeks tracked | 2 |
| Average week | -0.08% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -1.90% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +35.1% | +17 |
| XLM perp | +26.0% | +3 |
| AAVE perp | +19.0% | +4 |
| ADA perp | +10.2% | +5 |
| SOL perp | +7.9% | +2 |
| LTC perp | +7.3% | +3 |
| BTC perp | +7.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -37.4% | -10 |
| BCH perp | -36.7% | -16 |
| NEAR perp | -27.4% | -3 |
| ZEC perp | -21.8% | -4 |
| BNB perp | -19.3% | -3 |
| DOT perp | -14.3% | -16 |
| XRP perp | -5.7% | -1 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.1% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
