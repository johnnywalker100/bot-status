# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8952** (-10.48% since start) |
| Peak / drawdown | 1.0141 / -11.73% |
| Ticks recorded | 685 |
| Last tick | 2026-08-21T18:08:54.588629+00:00 (+0.0685%) |
| Risk rails | normal (dd -11.7%) |
| Data source | coinbase-cfm (bar 2026-08-21 17:00:00+00:00) |
| Gross leverage | 1.82x |
| Weeks tracked | 4 |
| Average week | -0.79% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.19% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +25.1% | +4 |
| SOL perp | +15.4% | +3 |
| BNB perp | +15.2% | +2 |
| BCH perp | +13.1% | +4 |
| AVAX perp | +12.0% | +14 |
| ETH perp | +10.8% | +4 |
| XLM perp | +10.8% | +1 |
| ADA perp | +9.8% | +4 |
| DOT perp | +9.1% | +9 |
| LINK perp | +6.5% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -23.7% | -5 |
| NEAR perp | -21.3% | -2 |
| LTC perp | -8.7% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
