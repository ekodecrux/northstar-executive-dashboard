# Northstar Executive Dashboard

Plain-local CEO dashboard wireframe for delivery, milestones, track heatmap, risks and finance.

## Run

From this folder, serve the static site:

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

Then open `http://localhost:4173` (or the sandbox preview URL if using the hosted session).

## Workbook import

Use the **Import workbook** menu to load `.xlsx`, `.xls`, or `.csv` files. The first sheet is read for Excel files. The current wireframe maps common column labels such as Track, Status, Confidence, Updated, Owner, Risk and Mitigation, then refreshes the track heatmap and updates view.

This version ships with realistic sample data to demonstrate the CEO-level view before a workbook is connected.
