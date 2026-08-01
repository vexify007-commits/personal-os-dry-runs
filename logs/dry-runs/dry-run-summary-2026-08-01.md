# Alpaca paper-bot dry-run summary — 2026-08-01

Window: 2026-07-31T19:20:50.658Z to 2026-08-01T19:20:50.658Z (past 24 hours)

## Activity

- Successful dry-run cycles persisted to Supabase: **1**
- Signal observations: **2** across MSFT, ORCL
- BUY: **0** · SELL: **0** · HOLD: **2**
- Safe paper-order proposals generated: **0**
- Automatic paper orders accepted by Alpaca: **0**
- Automatic paper submissions blocked or rejected: **0**
- Actionable signals blocked by risk/memory/state gates: **0**
- Cycles observed while the market was open: **1**

## Outcome tracking

The monitor records signals, safety decisions, proposal previews, and automatic paper-order acceptance or blocking. Closed-trade outcomes and realized P&L are not yet calculated here, so wins, losses, and profitability are not reported.

## Notable signals

No BUY or SELL signals were recorded in this window; all recorded observations were HOLD.

---
Source: Personal OS Supabase `audit_log` rows where `action = trading_monitor_sync`. Only successfully persisted cycles are counted.
