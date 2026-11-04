# Changelog

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
