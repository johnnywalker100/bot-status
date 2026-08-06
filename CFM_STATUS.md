# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9192** (-8.08% since start) |
| Peak / drawdown | 1.0141 / -9.36% |
| Ticks recorded | 310 |
| Last tick | 2026-08-06T01:09:18.814874+00:00 (+0.1166%) |
| Risk rails | normal (dd -9.3%) |
| Data source | coinbase-cfm (bar 2026-08-06 00:00:00+00:00) |
| Gross leverage | 3.08x |
| Weeks tracked | 2 |
| Average week | -0.26% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -2.26% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +37.3% | +18 |
| XLM perp | +26.9% | +3 |
| AAVE perp | +19.6% | +4 |
| ADA perp | +10.4% | +5 |
| SOL perp | +8.0% | +2 |
| LTC perp | +7.4% | +3 |
| BTC perp | +7.0% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -41.8% | -11 |
| BCH perp | -39.6% | -17 |
| NEAR perp | -27.9% | -3 |
| BNB perp | -25.9% | -4 |
| ZEC perp | -22.1% | -4 |
| DOT perp | -15.6% | -17 |
| XRP perp | -11.5% | -2 |
| LINK perp | -4.4% | -1 |
| AVAX perp | -2.2% | -3 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
