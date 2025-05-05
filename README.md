# Healthcare-dashboard
interactive Healthcare Analytics Dashboard in Power BI that turns raw hospital‑visit CSVs into an executive, one‑page report.
Scope – Covers patient visits, costs (medication, treatment, room charges), insurance coverage, and satisfaction scores.

Data Pipeline – Import → clean with Power Query → star‑schema model with a custom Date table and a disconnected “Calc” table for measures.

KPI Layer – Six headline indicators (Billing Amount, Medication Cost, Treatment Cost, Insurance Covered, Room Charges, Out‑of‑Pocket) plus dynamic averages and billing‑per‑visit metrics.

Visual Insights

Azure Map(Not avilable so used Map to vizualize it differently and used Bubble to show the area that is affected the most.

%‑of‑Grand‑Total bar charts for Procedures and Departments.

100 % stacked bar showing Service‑Type mix by Diagnosis.

UX Features – Light/Dark theme switcher (PNG + bookmark), hide‑and‑show slicer panel, neatly foldered measures, and a PowerPoint‑designed gradient background with rounded KPI cards.

In short, the project showcases end‑to‑end BI skills—data wrangling, DAX modelling,Power Query, advanced visuals, and polished UI design—wrapped in a portfolio‑ready Power BI report.

## ✨ Key Features
- Automated ETL  
  Text/CSV import → Power Query cleansing → relational model with auto‑relationships
- Disconnected “Calc” Table for measures & foldered organisation
- Core KPIs (Billing, Medication, Treatment, Insurance, Room Charges, Out‑of‑Pocket)
- Dynamic Averages (length of stay, satisfaction, billing per visit, etc.)
- Geospatial Insight (Azure Map bubbles toggled by _State_ / _City_ field parameter)
- % of Grand‑Total Bars for Procedure & Department comparisons
- Theme Switcher between light & dark backgrounds (bookmark + custom PNG)
- Branded Layout – gradient background from PowerPoint + rounded KPI cards
