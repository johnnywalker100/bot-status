# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9143** (-8.57% since start) |
| Peak / drawdown | 1.0141 / -9.84% |
| Ticks recorded | 301 |
| Last tick | 2026-08-05T16:08:25.553162+00:00 (-0.1115%) |
| Risk rails | normal (dd -9.8%) |
| Data source | coinbase-cfm (bar 2026-08-05 15:00:00+00:00) |
| Gross leverage | 3.12x |
| Weeks tracked | 2 |
| Average week | -0.52% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.78% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +34.9% | +17 |
| XLM perp | +27.4% | +3 |
| AAVE perp | +19.8% | +4 |
| SOL perp | +16.2% | +4 |
| ADA perp | +14.6% | +7 |
| BTC perp | +7.1% | +1 |
| AVAX perp | +5.1% | +7 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -34.4% | -9 |
| BCH perp | -23.3% | -10 |
| XRP perp | -23.2% | -4 |
| ZEC perp | -22.7% | -4 |
| LTC perp | -22.2% | -9 |
| BNB perp | -19.7% | -3 |
| LINK perp | -17.8% | -4 |
| DOT perp | -14.9% | -16 |
| NEAR perp | -9.3% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
