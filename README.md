# AEL (Flour) — Production Performance / OEE Loss Diagnostic

Single-file HTML dashboard for **AEL — Flour Milling**, shifts A–D.

## Features
- **Toggle:** Last day (12-Oct-2026) and Month-to-date (Oct 2026)
- OEE KPIs (Availability / Performance / Quality / Overall OEE) vs targets **A90 / P86 / Q97 / OEE75**
- Where time is going (planned / available / down)
- OEE by product (Maida, Atta, Atta+Suji, Atta+Suji+B.Atta) + Find-the-bottleneck
- Top downtime + downtime by category (min)
- **Opportunity Loss = NPT min ÷ cycle time (2.4 min/MT)** → lost output (MT)
- Production & OEE trend (last 16 days)
- Shift Action Board — downtime reasons with **responsible team** tagging
- Shift OEE and Gemba walk

## Data source
`Production Report` and `Flour Breakdown` tabs of the AEL (Flour) OEE sheet.

## Usage
Open `index.html` in any browser. Use the toggle to switch reporting period. Print (Ctrl+P) to PDF for a one-pager.

## Notes
- OEE = Availability × Performance × Quality.
- Data through 12-Oct-2026.
