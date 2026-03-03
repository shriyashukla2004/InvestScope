# 🌍 InvestScope — IFC Global Portfolio Intelligence Dashboard

A professional, multi-page **Power BI Dashboard** built on the IFC 
Investment Services dataset from the World Bank Disclosure Portal. 
This project transforms raw investment data into actionable insights 
across geography, industry, risk, and time.

---

## 📊 Dashboard Overview

| Page | Title | Key Visuals |
|------|-------|-------------|
| 1 | Executive Summary | KPI Cards, Bar Chart, Donut Charts, Line Chart |
| 2 | Geographic Analysis | Filled Map, Treemap, Top 10 Bar Chart |
| 3 | Industry Breakdown | Stacked Bar, Donut, Matrix Table |
| 4 | Trends Over Time | Combo Chart, Area Chart, Clustered Columns |
| 5 | Portfolio Health | Gauge, Scatter, Risk Table, Progress Bars |
| 6 | Project Detail | Drillthrough Table, Timeline, Product Mix |

---

## 🔢 Key Metrics

- 💰 **$94.7B** Total Investment Portfolio
- 📁 **6,870** Projects Analysed
- 🌍 **142** Countries Covered
- 🏭 **12** Industry Sectors
- 📅 Data Period: **1997 – February 2026**

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development & visualization
- **Power Query Editor** — Data cleaning & transformation
- **DAX** — Calculated measures & KPIs
- **IFC Disclosure Portal** — Data source
- **Python (pandas)** — Exploratory data analysis

---

## 🧹 Data Cleaning Steps

- Fixed mixed date formats (MM/DD/YYYY and MM-DD-YYYY)
- Handled 6 date columns using locale-based type conversion
- Replaced null investment values with 0 for aggregation
- Cleaned HTML entities (&amp;) in Industry and Department columns
- Renamed long column names for dashboard readability
- Removed redundant columns (Project URL, Document Type, As of Date)

---

## 📐 DAX Measures Built

### Basic
- Total Investment, Total Projects, Active Projects
- Total Loans, Total Equity, Total Guarantees

### Intermediate
- Active Projects %, Loan Share %, YoY Growth
- Avg Investment per Project, Countries Invested In

### Advanced
- Rolling 3-Year Average, Cumulative Investment
- Country Rank (RANKX), Top Country Concentration %
- YoY Growth Label (dynamic text measure)

---

## 🎨 Design

- **Color Scheme:** Clean Corporate Light
  - Background: `#F4F6F9` | Cards: `#FFFFFF`
  - Primary: `#1A56DB` | Secondary: `#0E7C59`
  - Accent: `#E07B39` | Alert: `#C0392B`
- **Font:** Calibri (titles) + Calibri Light (body)
- **Layout:** Consistent header bar, KPI row, chart section, footer
