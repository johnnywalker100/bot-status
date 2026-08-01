# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9512** (-4.88% since start) |
| Peak / drawdown | 1.0141 / -6.20% |
| Ticks recorded | 197 |
| Last tick | 2026-08-01T08:08:24.925982+00:00 (+0.6560%) |
| Risk rails | normal (dd -6.2%) |
| Data source | coinbase-cfm (bar 2026-08-01 07:00:00+00:00) |
| Gross leverage | 3.07x |
| Weeks tracked | 1 |
| Average week | +2.91% |
| Weeks >= +3% | 0% |
| Best / worst week | +2.91% / +2.91% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +19.2% | +4 |
| XLM perp | +18.0% | +2 |
| ETH perp | +15.7% | +8 |
| ADA perp | +14.4% | +8 |
| DOT perp | +14.4% | +18 |

| Short | Size | Contracts |
|---|---|---|
| DOGE perp | -51.3% | -14 |
| BNB perp | -31.0% | -5 |
| LTC perp | -30.4% | -13 |
| BCH perp | -28.8% | -13 |
| ZEC perp | -24.4% | -5 |
| LINK perp | -17.1% | -4 |
| BTC perp | -13.3% | -2 |
| NEAR perp | -8.7% | -1 |
| SOL perp | -7.7% | -2 |
| AVAX perp | -6.7% | -10 |
| XRP perp | -5.6% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
