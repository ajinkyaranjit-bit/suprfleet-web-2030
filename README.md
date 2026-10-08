# SuprFleet Web 2030

> SuprFleet turns fleet signals into decisions you can verify, and handles routine work within limits you set.

A working prototype for a design take-home: the most useful way for a Head of Operations to run a mixed fleet of 500 assets in 2030.

**Scenario:** Vikram Deshmukh, Head of Operations at Konkan Infra Services (fictional). 260 trucks, 120 generators, 80 inverters and batteries, 40 solar charging stations across 38 sites.

## Try it

Open `index.html` in a browser, or the live link. Press **Reset demo** before each run.

The core flow: **Today → Proposal → Evidence → Approve → Track → Automation rules**, plus Activity, an Ask layer (⌘K) and a state menu for hard states (dense day, stale data, empty, action failed).

## What's in here

| Path | What it is |
|---|---|
| `index.html` | Prototype v3.2 (frozen), single file |
| `versions/` | Earlier prototype versions (v1, v2, v3) and the first thinking board, kept for history |

## Notes

- Single-file HTML. React 18.3.1 and Babel standalone load from public CDNs, so it needs internet.
- All data is illustrative. Model figures (for example the 45% → 8% failure chance) are assumptions to show the reasoning, not real predictions.
- Timers are simulated. Switching state resets the demo.
- Colour contrast has not been formally audited yet.
- Next step: port to a component-based React app.
