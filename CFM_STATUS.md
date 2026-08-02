# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9509** (-4.91% since start) |
| Peak / drawdown | 1.0141 / -6.23% |
| Ticks recorded | 230 |
| Last tick | 2026-08-02T17:08:32.136012+00:00 (-0.5337%) |
| Risk rails | normal (dd -6.2%) |
| Data source | coinbase-cfm (bar 2026-08-02 16:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 1 |
| Average week | +2.87% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.87% / +2.87% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.5% | +3 |
| ETH perp | +15.7% | +8 |
| ADA perp | +13.9% | +7 |
| DOT perp | +11.7% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.3% | -12 |
| BNB perp | -43.3% | -7 |
| LTC perp | -25.9% | -11 |
| BCH perp | -24.7% | -11 |
| ZEC perp | -24.7% | -5 |
| LINK perp | -21.8% | -5 |
| BTC perp | -13.3% | -2 |
| XRP perp | -11.4% | -2 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -8.3% | -12 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
