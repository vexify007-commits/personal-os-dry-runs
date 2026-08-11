# Alpaca paper-bot dry-run summary — 2026-08-11

Window: 2026-08-10T19:37:54.025Z to 2026-08-11T19:37:54.025Z (past 24 hours)

## Activity

- Successful dry-run cycles persisted to Supabase: **1**
- Signal observations: **2** across MSFT, ORCL
- BUY: **1** · SELL: **0** · HOLD: **1**
- Safe paper-order proposals generated: **1**
- Automatic paper orders accepted by Alpaca: **0**
- Automatic paper submissions blocked or rejected: **1**
- Actionable signals blocked by risk/memory/state gates: **0**
- Cycles observed while the market was open: **1**

## Outcome tracking

The monitor records signals, safety decisions, proposal previews, and automatic paper-order acceptance or blocking. Closed-trade outcomes and realized P&L are not yet calculated here, so wins, losses, and profitability are not reported.

## Notable signals

| Bar time | Symbol | Signal | Price | Proposal | Automatic execution | Decision |
| --- | --- | ---: | ---: | --- | --- | --- |
| 2026-08-11T19:29:59.999Z | MSFT | BUY | $502.86 | Yes | blocked | DRY-RUN PROPOSAL CREATED AND LOGGED LOCALLY. Nothing was sent to Alpaca. |

---
Source: Personal OS Supabase `audit_log` rows where `action = trading_monitor_sync`. Only successfully persisted cycles are counted.
