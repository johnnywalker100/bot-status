# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9589** (-4.11% since start) |
| Peak / drawdown | 1.0141 / -5.45% |
| Ticks recorded | 225 |
| Last tick | 2026-08-02T12:08:18.417419+00:00 (+0.4867%) |
| Risk rails | normal (dd -5.4%) |
| Data source | coinbase-cfm (bar 2026-08-02 11:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +3.73% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.73% / +3.73% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.3% | +3 |
| ETH perp | +17.4% | +9 |
| ADA perp | +13.8% | +7 |
| DOT perp | +11.6% | +14 |
| AAVE perp | +4.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -43.8% | -12 |
| BNB perp | -42.5% | -7 |
| LTC perp | -25.6% | -11 |
| ZEC perp | -24.5% | -5 |
| BCH perp | -24.3% | -11 |
| LINK perp | -21.6% | -5 |
| BTC perp | -13.2% | -2 |
| XRP perp | -11.3% | -2 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -8.3% | -12 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
