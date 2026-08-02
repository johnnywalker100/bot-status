# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9542** (-4.58% since start) |
| Peak / drawdown | 1.0141 / -5.91% |
| Ticks recorded | 224 |
| Last tick | 2026-08-02T11:08:24.162380+00:00 (+0.1081%) |
| Risk rails | normal (dd -5.9%) |
| Data source | coinbase-cfm (bar 2026-08-02 10:00:00+00:00) |
| Gross leverage | 3.03x |
| Weeks tracked | 1 |
| Average week | +3.23% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.23% / +3.23% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.5% | +3 |
| ETH perp | +15.7% | +8 |
| ADA perp | +13.7% | +7 |
| DOT perp | +11.6% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.0% | -12 |
| BNB perp | -42.8% | -7 |
| LTC perp | -25.7% | -11 |
| ZEC perp | -24.8% | -5 |
| BCH perp | -24.4% | -11 |
| LINK perp | -21.8% | -5 |
| BTC perp | -13.2% | -2 |
| XRP perp | -11.3% | -2 |
| NEAR perp | -9.0% | -1 |
| AVAX perp | -8.3% | -12 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
