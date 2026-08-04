# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9408** (-5.92% since start) |
| Peak / drawdown | 1.0141 / -7.23% |
| Ticks recorded | 264 |
| Last tick | 2026-08-04T03:09:06.527953+00:00 (-0.1050%) |
| Risk rails | normal (dd -7.2%) |
| Data source | coinbase-cfm (bar 2026-08-04 02:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 2 |
| Average week | +0.89% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.04% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +29.7% | +15 |
| XLM perp | +18.1% | +2 |
| SOL perp | +15.7% | +4 |
| AAVE perp | +14.7% | +3 |
| ADA perp | +8.3% | +4 |
| AVAX perp | +5.1% | +7 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -37.7% | -6 |
| LTC perp | -35.3% | -15 |
| DOGE perp | -29.9% | -8 |
| BCH perp | -22.6% | -10 |
| ZEC perp | -20.5% | -4 |
| BTC perp | -13.5% | -2 |
| LINK perp | -13.1% | -3 |
| DOT perp | -12.5% | -14 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
