# Alpaca paper-bot dry-run summary — 2026-07-29

Window: 2026-07-28T19:51:24.955Z to 2026-07-29T19:51:24.955Z (past 24 hours)

## Activity

- Successful dry-run cycles persisted to Supabase: **1**
- Signal observations: **2** across MSFT, ORCL
- BUY: **1** · SELL: **0** · HOLD: **1**
- Safe paper-order proposals generated: **0**
- Actionable signals blocked by risk/memory/state gates: **1**
- Cycles observed while the market was open: **1**

## Outcome tracking

The monitor currently records signals, safety decisions, and proposal previews—not closed-trade outcomes or realized P&L. Wins, losses, and profitability are therefore not reported here.

## Notable signals

| Bar time | Symbol | Signal | Price | Proposal | Decision |
| --- | --- | ---: | ---: | --- | --- |
| 2026-07-29T19:29:59.999Z | MSFT | BUY | $395.95 | No | NO PROPOSAL - asset class is undefined, not us_equity. |

---
Source: Personal OS Supabase `audit_log` rows where `action = trading_monitor_sync`. Only successfully persisted cycles are counted.
