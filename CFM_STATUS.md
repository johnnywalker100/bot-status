# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9605** (-3.95% since start) |
| Peak / drawdown | 1.0141 / -5.29% |
| Ticks recorded | 137 |
| Last tick | 2026-07-29T19:09:01.712982+00:00 (-0.0569%) |
| Risk rails | normal (dd -5.3%) |
| Data source | coinbase-cfm (bar 2026-07-29 18:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +3.91% |
| Weeks >= +3% | 100% |
| Best / worst week | +3.91% / +3.91% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +20.6% | +4 |
| ADA perp | +19.2% | +11 |
| XLM perp | +17.9% | +2 |
| BCH perp | +13.1% | +6 |
| ETH perp | +9.9% | +5 |
| DOT perp | +9.6% | +12 |
| SOL perp | +3.8% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -47.8% | -13 |
| LTC perp | -37.8% | -16 |
| BNB perp | -29.7% | -5 |
| NEAR perp | -25.5% | -3 |
| BTC perp | -20.1% | -3 |
| LINK perp | -17.4% | -4 |
| ZEC perp | -14.5% | -3 |
| AVAX perp | -8.7% | -13 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
