# Alpaca paper-bot dry-run summary — 2026-09-09

Window: 2026-09-08T19:03:05.729Z to 2026-09-09T19:03:05.729Z (past 24 hours)

## Activity

- Successful dry-run cycles persisted to Supabase: **1**
- Signal observations: **2** across MSFT, ORCL
- BUY: **0** · SELL: **1** · HOLD: **1**
- Safe paper-order proposals generated: **0**
- Automatic paper orders accepted by Alpaca: **0**
- Automatic paper submissions blocked or rejected: **0**
- Actionable signals blocked by risk/memory/state gates: **1**
- Cycles observed while the market was open: **1**

## Outcome tracking

The monitor records signals, safety decisions, proposal previews, and automatic paper-order acceptance or blocking. Closed-trade outcomes and realized P&L are not yet calculated here, so wins, losses, and profitability are not reported.

## Notable signals

| Bar time | Symbol | Signal | Price | Proposal | Automatic execution | Decision |
| --- | --- | ---: | ---: | --- | --- | --- |
| 2026-09-09T15:59:59.999Z | ORCL | SELL | $161.45 | No | None | NO PROPOSAL - position/open-order state gate failed. |

---
Source: Personal OS Supabase `audit_log` rows where `action = trading_monitor_sync`. Only successfully persisted cycles are counted.
