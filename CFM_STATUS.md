# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.9480** (-5.20% since start) |
| Peak / drawdown | 1.0141 / -6.52% |
| Ticks recorded | 260 |
| Last tick | 2026-08-03T23:11:44.380318+00:00 (+0.2979%) |
| Risk rails | normal (dd -6.5%) |
| Data source | coinbase-cfm (bar 2026-08-03 22:00:00+00:00) |
| Gross leverage | 3.02x |
| Weeks tracked | 2 |
| Average week | +1.27% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / +0.80% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| ETH perp | +31.3% | +16 |
| XLM perp | +27.1% | +3 |
| SOL perp | +15.5% | +4 |
| ADA perp | +10.3% | +5 |
| AAVE perp | +4.8% | +1 |
| DOT perp | +1.7% | +2 |

| Short | Size | Contracts |
|---|---|---|
| BNB perp | -37.3% | -6 |
| LTC perp | -37.3% | -16 |
| DOGE perp | -33.3% | -9 |
| BCH perp | -22.5% | -10 |
| ZEC perp | -20.2% | -4 |
| LINK perp | -17.2% | -4 |
| XRP perp | -17.0% | -3 |
| BTC perp | -13.4% | -2 |
| NEAR perp | -9.1% | -1 |
| AVAX perp | -3.5% | -5 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
