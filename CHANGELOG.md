# Changelog

## 1.3.0 — 2026-11-05

Feedback button.

- **Feedback** button in the header, next to the light/dark toggle. It opens a short form (in a new tab) for bugs, questions and ideas about this app

## 1.2.0 — 2026-11-04

Nordic theme, light and dark modes, accessibility.

- New look shared across the CAITO tool suite: an airy Nordic palette with its own accent and icon (also the browser tab icon)
- **Light / dark toggle** in the header. It follows your device until you choose, then remembers your choice across all the tools
- Inter font (SIL Open Font License) is now built into the file, so the app makes no font requests and looks the same everywhere
- Accessibility: every control has a label, all text meets WCAG AA contrast in both modes, and keyboard focus is clearly visible
- Gains a light/dark toggle (it only followed the device setting before); charts redraw when you switch.

## 1.1.0 — 2026-11-03

Clear split between sample data and a real client forecast.

- Skuld opens on clearly labeled **Sample data**: a striped banner, a SAMPLE tag on the headline figure, "sample data" in the result line and the page title, and a SAMPLE DATA header on the copied summary
- **Start new client forecast** clears every client figure (payroll, headcount, revenue, COGS, records exposed) and keeps the sourced reference rates (fees, penalties, recovery)
- A client name typed over sample data is flagged and carried into the new forecast
- Client forecasts show a **Client forecast** banner with the client's name and which key inputs are still missing; missing fields are outlined, and the headline waits for payroll and revenue
- **Load sample data** and **New forecast** ask for confirmation before replacing a client forecast
- Replaces the old "Reset to defaults" button

## 1.0.0 — 2026-11-03

First public release.

- Downtime cost per hour from idle payroll, lost revenue and cost of goods, with an operating schedule, staff affected, productivity lost, benefits load and share of revenue truly lost
- Payroll as a yearly total or average hourly rate; revenue yearly or monthly; cost of goods yearly or per head, treated as avoided or still incurred
- Outage length from 15 minutes to 60 working days, by typed value or slider
- Incident / ransomware mode: records exposed across seven data types, with a data-size-to-record-count helper
- Notification, credit monitoring, PCI, HIPAA (tier and annual cap), CCPA, GDPR and other fines
- Recovery cost and ransom estimate by revenue band and industry, with an override
- Cross-check against IBM cost-per-record and industry breach averages
- Cumulative cost chart, milestone table and copyable summary
- Plain-English **!** help on every section, and a "How the math works & sources" page with worked examples and a sourced list of every default value
- Client / location field, light and dark themes
- Version check against a public `skuld.json`, with repository-move support
- Footer with authorship, LinkedIn and Portfolio Toolbox links
