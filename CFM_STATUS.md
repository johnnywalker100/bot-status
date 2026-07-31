# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9515** (-4.85% since start) |
| Peak / drawdown | 1.0141 / -6.18% |
| Ticks recorded | 175 |
| Last tick | 2026-07-31T09:08:47.699002+00:00 (+0.1254%) |
| Risk rails | normal (dd -6.2%) |
| Data source | coinbase-cfm (bar 2026-07-31 08:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 1 |
| Average week | +2.93% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.93% / +2.93% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ADA perp | +21.5% | +12 |
| AAVE perp | +20.5% | +4 |
| XLM perp | +17.8% | +2 |
| DOT perp | +11.2% | +14 |
| ETH perp | +9.9% | +5 |
| SOL perp | +7.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.4% | -14 |
| LTC perp | -37.9% | -16 |
| BNB perp | -24.9% | -4 |
| BCH perp | -24.6% | -11 |
| ZEC perp | -19.3% | -4 |
| LINK perp | -17.5% | -4 |
| BTC perp | -13.4% | -2 |
| AVAX perp | -10.2% | -15 |
| NEAR perp | -8.7% | -1 |
| XRP perp | -5.7% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
