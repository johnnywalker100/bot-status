# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9583** (-4.17% since start) |
| Peak / drawdown | 1.0141 / -5.51% |
| Ticks recorded | 215 |
| Last tick | 2026-08-02T02:08:41.512312+00:00 (-1.3213%) |
| Risk rails | normal (dd -5.5%) |
| Data source | coinbase-cfm (bar 2026-08-02 01:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 1 |
| Average week | +3.67% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.67% / +3.67% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.1% | +3 |
| ETH perp | +15.7% | +8 |
| ADA perp | +14.8% | +8 |
| DOT perp | +11.6% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -43.8% | -12 |
| BNB perp | -42.3% | -7 |
| LTC perp | -25.7% | -11 |
| ZEC perp | -24.6% | -5 |
| BCH perp | -24.0% | -11 |
| LINK perp | -21.5% | -5 |
| BTC perp | -13.2% | -2 |
| XRP perp | -11.2% | -2 |
| AVAX perp | -9.8% | -15 |
| NEAR perp | -8.9% | -1 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
