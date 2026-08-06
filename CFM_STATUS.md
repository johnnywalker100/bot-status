# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9170** (-8.30% since start) |
| Peak / drawdown | 1.0141 / -9.57% |
| Ticks recorded | 312 |
| Last tick | 2026-08-06T03:10:05.153694+00:00 (+0.1848%) |
| Risk rails | normal (dd -9.6%) |
| Data source | coinbase-cfm (bar 2026-08-06 02:00:00+00:00) |
| Gross leverage | 3.09x |
| Weeks tracked | 2 |
| Average week | -0.37% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.49% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +37.2% | +18 |
| XLM perp | +26.5% | +3 |
| AAVE perp | +19.2% | +4 |
| ADA perp | +10.4% | +5 |
| SOL perp | +8.0% | +2 |
| LTC perp | +7.3% | +3 |
| BTC perp | +7.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| BCH perp | -41.8% | -18 |
| DOGE perp | -41.7% | -11 |
| NEAR perp | -27.8% | -3 |
| BNB perp | -25.9% | -4 |
| ZEC perp | -22.1% | -4 |
| DOT perp | -15.6% | -17 |
| XRP perp | -11.4% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
