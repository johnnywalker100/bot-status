# US CFM Desk - Paper-Trading Status

*Coinbase CFTC-regulated perp-style futures (CDE), paper-traded at a
$10,000 account with whole-contract rounding, posted hourly funding,
taker fees + slippage + per-contract commission floor. Simulated - no real
money. Book: slow momentum 60% / funding carry 40% (see cfm_backtest.py).*

![equity](cfm_status_equity.png)

| | |
|---|---|
| **Equity** | **0.8509** (-14.91% since start) |
| Peak / drawdown | 1.0141 / -16.10% |
| Ticks recorded | 667 |
| Last tick | 2026-08-21T00:08:35.875997+00:00 (+0.2285%) |
| Risk rails | brake: drawdown -16.1% <= -12%, half size |
| Data source | coinbase-cfm (bar 2026-08-20 23:00:00+00:00) |
| Gross leverage | 1.66x |
| Weeks tracked | 4 |
| Average week | -2.00% |
| Weeks >= +3% | 0% |
| Best / worst week | +1.74% / -7.03% |

## Positions (weight of account / whole contracts)

| Long | Size | Contracts |
|---|---|---|
| AAVE perp | +29.1% | +5 |
| XLM perp | +10.7% | +1 |
| AVAX perp | +10.3% | +12 |
| ADA perp | +9.4% | +4 |
| BCH perp | +7.9% | +3 |
| BNB perp | +7.7% | +1 |
| ETH perp | +5.5% | +2 |
| SOL perp | +5.2% | +1 |

| Short | Size | Contracts |
|---|---|---|
| NEAR perp | -20.8% | -2 |
| DOGE perp | -18.9% | -4 |
| LTC perp | -16.9% | -6 |
| BTC perp | -8.6% | -1 |
| XRP perp | -7.4% | -1 |
| LINK perp | -6.3% | -1 |
| DOT perp | -1.0% | -1 |

*Every position is an integer number of CDE contracts at the configured
account size - exactly what a live account could hold.*
