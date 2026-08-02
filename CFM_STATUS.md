# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9506** (-4.94% since start) |
| Peak / drawdown | 1.0141 / -6.26% |
| Ticks recorded | 221 |
| Last tick | 2026-08-02T08:08:25.237391+00:00 (+0.0050%) |
| Risk rails | normal (dd -6.3%) |
| Data source | coinbase-cfm (bar 2026-08-02 07:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 1 |
| Average week | +2.84% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.84% / +2.84% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.7% | +3 |
| ETH perp | +15.8% | +8 |
| ADA perp | +13.7% | +7 |
| DOT perp | +11.7% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.4% | -12 |
| BNB perp | -43.0% | -7 |
| LTC perp | -25.9% | -11 |
| ZEC perp | -24.8% | -5 |
| BCH perp | -24.5% | -11 |
| LINK perp | -22.0% | -5 |
| BTC perp | -13.3% | -2 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -8.3% | -12 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
