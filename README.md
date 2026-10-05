# Sustainable Sourcing & Fabric Defect Diagnostic Dashboard

A 4-page Power BI report analysing 1,559 fabric defects across 250 inspections and 7 suppliers, to find where defects come from and which suppliers carry the most risk.

## Business question
Which suppliers, fabric types and defect types drive quality problems, and does sourcing certification matter?

## Key findings
- Hollywood by H. Textiles Company accounts for 37.7% of all defects, with the highest defect rate (12.51) and the highest risk score (32.94).
- Mixed/Sourced fabric has the most defects (588) and comes from a single supplier with no certification listed.
- Hollywood and Shanghai Baida together cause about 53% of all defects.
- Only 1 of 7 suppliers has a listed certification (GOTS), and it is among the better performers.
- Hole is the most common defect type (344 defects, 22.07%).

## Dashboard pages

### 1. Overview
Key numbers, defects by fabric type, defect type breakdown and the headline insight cards.

![Overview](/01_overview.png)

### 2. Trends
Defect rate over time, with date, fabric type and supplier filters.

![Trends](/02_trends.png)

### 3. Root Cause
A decomposition tree that traces defects from fabric type to defect type to supplier.

![Root Cause](/03_root_cause.png)

### 4. Supplier Scorecard
Supplier ranking with risk colour coding, certification status and a recommendation.

![Supplier Scorecard](/04_supplier_scorecard.png)

## Recommendation
Review or replace Hollywood by H. Textiles and Shanghai Baida, and prioritize certified suppliers in future sourcing.

## Tools and techniques
- Power BI Desktop
- DAX measures (total defects, defect rate, weighted risk score, top supplier, certified supplier share)
- Data modelling with relationships across multiple tables
- Decomposition tree, conditional formatting, page navigation and cross-filtering

## Files in this repository
- `fabric_defect_dashboard.pbix`: the Power BI report (open in Power BI Desktop)
- `dashboard.pdf`: PDF export of all pages ([Download the PDF](https://github.com/msandhiya124-cmyk/fabric-defect-diagnostic-dashboard/raw/main/dashboard.pdf))

## How to open the report
Download `fabric_defect_dashboard.pbix` and open it in Power BI Desktop (free, Windows only).

## Notes and limitations
- Defect rate means defects per inspection, not a percentage.
- "None Listed" means no certification appears in the data. It does not prove a supplier has none.
- Only one supplier is certified, so the link between certification and quality is suggestive, not proven.
- The inspection data covers January to March 2015.

## Author
Sandhiya M | [LinkedIn](https://www.linkedin.com/in/sandhiya-m-b61504368) | msandhiya124@gmail.com
