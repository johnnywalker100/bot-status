# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9458** (-5.42% since start) |
| Peak / drawdown | 1.0141 / -6.74% |
| Ticks recorded | 232 |
| Last tick | 2026-08-02T19:08:30.700629+00:00 (-0.2241%) |
| Risk rails | normal (dd -6.7%) |
| Data source | coinbase-cfm (bar 2026-08-02 18:00:00+00:00) |
| Gross leverage | 3.01x |
| Weeks tracked | 1 |
| Average week | +2.32% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.32% / +2.32% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.7% | +3 |
| ETH perp | +15.9% | +8 |
| ADA perp | +14.0% | +7 |
| DOT perp | +11.8% | +14 |
| AAVE perp | +4.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.9% | -12 |
| BNB perp | -37.4% | -6 |
| LTC perp | -26.1% | -11 |
| ZEC perp | -25.1% | -5 |
| BCH perp | -24.8% | -11 |
| LINK perp | -22.0% | -5 |
| BTC perp | -13.4% | -2 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -8.4% | -12 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
