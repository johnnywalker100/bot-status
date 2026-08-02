# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9389** (-6.11% since start) |
| Peak / drawdown | 1.0141 / -7.41% |
| Ticks recorded | 233 |
| Last tick | 2026-08-02T20:08:52.280948+00:00 (-0.7263%) |
| Risk rails | normal (dd -7.4%) |
| Data source | coinbase-cfm (bar 2026-08-02 19:00:00+00:00) |
| Gross leverage | 2.98x |
| Weeks tracked | 1 |
| Average week | +1.58% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.58% / +1.58% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| XLM perp | +27.8% | +3 |
| ETH perp | +16.0% | +8 |
| ADA perp | +14.0% | +7 |
| DOT perp | +11.9% | +14 |
| AAVE perp | +4.9% | +1 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -45.1% | -12 |
| BNB perp | -37.6% | -6 |
| LTC perp | -26.3% | -11 |
| BCH perp | -25.0% | -11 |
| LINK perp | -22.1% | -5 |
| ZEC perp | -20.7% | -4 |
| BTC perp | -13.5% | -2 |
| XRP perp | -11.5% | -2 |
| NEAR perp | -9.1% | -1 |
| AVAX perp | -8.4% | -12 |
| SOL perp | -3.9% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
