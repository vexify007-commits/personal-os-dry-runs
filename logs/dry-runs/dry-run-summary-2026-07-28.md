# Alpaca paper-bot dry-run summary — 2026-07-28

Window: 2026-07-27T19:51:24.747Z to 2026-07-28T19:51:24.747Z (past 24 hours)

## Activity

- Successful dry-run cycles persisted to Supabase: **2**
- Signal observations: **4** across MSFT, ORCL
- BUY: **0** · SELL: **1** · HOLD: **3**
- Safe paper-order proposals generated: **0**
- Actionable signals blocked by risk/memory/state gates: **1**
- Cycles observed while the market was open: **2**

## Outcome tracking

The monitor currently records signals, safety decisions, and proposal previews—not closed-trade outcomes or realized P&L. Wins, losses, and profitability are therefore not reported here.

## Notable signals

| Bar time | Symbol | Signal | Price | Proposal | Decision |
| --- | --- | ---: | ---: | --- | --- |
| 2026-07-28T15:59:59.999Z | ORCL | SELL | $120.07 | No | NO PROPOSAL - position/open-order state gate failed. |

---
Source: Personal OS Supabase `audit_log` rows where `action = trading_monitor_sync`. Only successfully persisted cycles are counted.
