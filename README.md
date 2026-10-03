# walmart-sales-dashboard-2012
Google Sheets dashboard: sales efficiency ($/m²) and department share, Walmart 2012

## Objective
Analyze Walmart's 2012 sales performance through data cleaning, the creation of efficiency ($/m²) and sales-share KPIs, and an interactive dashboard to support strategic decision-making.

## Tools
Google Sheets · Pivot Tables · VLOOKUP · Conditional Formatting · Dashboards

## Workbook Structure
| Sheet | Description | Type |
|---|---|---|
| raw_ventas | Original weekly sales by store and department | Raw Data |
| raw_departamento | Department catalog with names | Lookup |
| raw_tiendas | Store catalog with type (A/B) and size in m² | Lookup |
| clean_ventas | Cleaned data with joined catalogs and standardized week | Clean Data |
| TD_KPI1 / TD_KPI2 | Pivot tables calculating efficiency and share metrics | Analysis |
| Dashboard | Interactive interface with filters and charts | Output |
| Resumen | Key findings and business implications (C→F→I method) | Reporting |

## KPIs
| KPI | Formula | Interpretation |
|---|---|---|
| Sales per m² | Total Sales / Store Size | Higher value = more efficiency per square meter |
| Share % | Department Sales / Total Sales | Identifies the core revenue-driving categories |

## Key Findings
1. **Grocery & Staples** is the most efficient department at **$652.82 per m²**. Allocating more floor space to it is worth considering, since it returns the most revenue per square meter.
2. **Grocery, Fresh Food and Baby Care** together account for more than **35%** of total sales, so any out-of-stock in these categories would seriously hurt the overall target.
3. Departments such as **Pet Care** have less than **5%** share. A product audit or a targeted marketing campaign is recommended to increase turnover.

## QA / Validation Checks
- Stores without an assigned department: **0**
- Store sizes (m²) equal to 0: **0**
- Zero or negative sales records: **27** (identified and reviewed)

## Files
- `Sprint_2_-_Proyecto_2__Resumen_Ejecutivo_de_Ventas_Walmart.xlsx`: cleaned data, analysis, dashboard, and executive summary.
- `images/`: screenshots of the pivot tables and charts.
- [View the Google Sheet](https://docs.google.com/spreadsheets/d/1O4dsu60kTM3kTLhTliWbZPb77JqT0qDT/edit?usp=sharing&ouid=116118350435914609784&rtpof=true&sd=true)
