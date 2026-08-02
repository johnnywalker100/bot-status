# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9711** (-2.89% since start) |
| Peak / drawdown | 1.0141 / -4.24% |
| Ticks recorded | 214 |
| Last tick | 2026-08-02T01:08:27.057530+00:00 (-0.2216%) |
| Risk rails | normal (dd -4.2%) |
| Data source | coinbase-cfm (bar 2026-08-02 00:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +5.06% |
| Weeks >= +3% | 100% |
| Best / worst week | +5.06% / +5.06% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +26.5% | +3 |
| ETH perp | +17.1% | +9 |
| ADA perp | +14.4% | +8 |
| DOT perp | +11.4% | +14 |
| AAVE perp | +4.7% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -42.8% | -12 |
| BNB perp | -41.5% | -7 |
| LTC perp | -25.0% | -11 |
| ZEC perp | -24.0% | -5 |
| BCH perp | -23.5% | -11 |
| LINK perp | -20.9% | -5 |
| BTC perp | -12.9% | -2 |
| XRP perp | -11.0% | -2 |
| AVAX perp | -10.2% | -16 |
| NEAR perp | -8.7% | -1 |
| SOL perp | -3.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
