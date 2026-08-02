# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9560** (-4.40% since start) |
| Peak / drawdown | 1.0141 / -5.74% |
| Ticks recorded | 228 |
| Last tick | 2026-08-02T15:08:28.036336+00:00 (-0.2465%) |
| Risk rails | normal (dd -5.7%) |
| Data source | coinbase-cfm (bar 2026-08-02 14:00:00+00:00) |
| Gross leverage | 3.04x |
| Weeks tracked | 1 |
| Average week | +3.42% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.42% / +3.42% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.5% | +3 |
| ETH perp | +17.5% | +9 |
| ADA perp | +13.9% | +7 |
| DOT perp | +11.7% | +14 |
| AAVE perp | +4.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -44.2% | -12 |
| BNB perp | -42.8% | -7 |
| LTC perp | -25.7% | -11 |
| ZEC perp | -24.7% | -5 |
| BCH perp | -24.4% | -11 |
| LINK perp | -21.7% | -5 |
| BTC perp | -13.2% | -2 |
| XRP perp | -11.3% | -2 |
| NEAR perp | -8.9% | -1 |
| AVAX perp | -8.3% | -12 |
| SOL perp | -3.8% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
