# CMP Pulse — Live Web Dashboard

A polished web dashboard for the CMP 2025–2026 mentorship tracker.

## Current version
The dashboard includes a snapshot of the `C11 2025-2026` worksheet from the uploaded Excel workbook.

## Make it live with Google Sheets
1. Upload/import the Excel workbook into Google Sheets.
2. Open the `C11 2025-2026` tab.
3. Share/publish the sheet so the data can be read by the dashboard.
4. In `index.html`, find `CONFIG.dataUrl` and paste the Google Sheets CSV endpoint:
   `https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/gviz/tq?tqx=out:csv&sheet=C11%202025-2026`
5. Host the folder with GitHub Pages, Netlify, or Vercel.
6. The dashboard will refresh every 60 seconds while the page is open.

## Design
- Clean operations-dashboard aesthetic
- Cyan / blue / lavender gradient accents
- KPI cards
- Milestone completion chart
- Status mix chart
- Search and milestone filters
- Mentee-level tracking table
- Responsive layout
