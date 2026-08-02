# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9581** (-4.19% since start) |
| Peak / drawdown | 1.0141 / -5.52% |
| Ticks recorded | 216 |
| Last tick | 2026-08-02T03:08:58.433227+00:00 (-0.0162%) |
| Risk rails | normal (dd -5.5%) |
| Data source | coinbase-cfm (bar 2026-08-02 02:00:00+00:00) |
| Gross leverage | 3.06x |
| Weeks tracked | 1 |
| Average week | +3.65% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.65% / +3.65% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.2% | +3 |
| ETH perp | +17.6% | +9 |
| ADA perp | +15.0% | +8 |
| DOT perp | +11.6% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -43.8% | -12 |
| BNB perp | -42.5% | -7 |
| LTC perp | -25.6% | -11 |
| ZEC perp | -24.7% | -5 |
| BCH perp | -24.0% | -11 |
| LINK perp | -21.6% | -5 |
| BTC perp | -13.2% | -2 |
| XRP perp | -11.2% | -2 |
| AVAX perp | -9.9% | -15 |
| NEAR perp | -8.9% | -1 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
