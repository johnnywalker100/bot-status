# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9644** (-3.56% since start) |
| Peak / drawdown | 1.0141 / -4.90% |
| Ticks recorded | 176 |
| Last tick | 2026-07-31T10:08:38.178385+00:00 (+1.3561%) |
| Risk rails | normal (dd -4.9%) |
| Data source | coinbase-cfm (bar 2026-07-31 09:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +4.33% |
| Weeks >= +3% | 100% |
| Best / worst week | +4.33% / +4.33% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.0% | +12 |
| AAVE perp | +20.2% | +4 |
| XLM perp | +17.6% | +2 |
| DOT perp | +11.0% | +14 |
| ETH perp | +9.7% | +5 |
| SOL perp | +7.6% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -50.3% | -14 |
| LTC perp | -39.6% | -17 |
| BNB perp | -24.4% | -4 |
| BCH perp | -23.5% | -11 |
| ZEC perp | -19.0% | -4 |
| LINK perp | -17.1% | -4 |
| BTC perp | -13.2% | -2 |
| AVAX perp | -10.0% | -15 |
| NEAR perp | -8.5% | -1 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
