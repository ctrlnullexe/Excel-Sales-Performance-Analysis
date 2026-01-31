# 📊 Sales Performance Analysis & Interactive Excel Dashboard

## Project Overview
This project demonstrates an end-to-end **sales performance analysis** built entirely in Excel.  
The goal was to simulate a real-world analyst workflow: starting from raw sales data, cleaning and transforming it, analyzing performance across multiple dimensions, and delivering insights through a clean, interactive dashboard.

Rather than focusing on static reporting, this project emphasizes **decision-ready analysis** that allows stakeholders to explore trends, compare segments, and quickly understand what’s driving performance.

---

## From Raw Data to Dashboard

### Raw Dataset
The analysis begins with a raw transactional sales dataset containing order dates, products, quantities, prices, and geographic information.

<img width="746" height="960" alt="raw_data" src="https://github.com/user-attachments/assets/42c91d1b-25ec-4901-bd5d-6b04c10e4aa5" />

<img width="1343" height="889" alt="raw_data png 2" src="https://github.com/user-attachments/assets/bdb0c4db-de5b-4fe3-a7dd-acba0cb12c44" />

<img width="553" height="921" alt="raw_data png 3" src="https://github.com/user-attachments/assets/f296ab47-657b-46e3-9b18-5644cfb6e40a" />




⬇️

### Final Interactive Dashboard
After cleaning, transforming, and analyzing the data, the final output is an interactive Excel dashboard with KPIs, charts, slicers, and a timeline for dynamic exploration.

<img width="1621" height="729" alt="dashboard_preview" src="https://github.com/user-attachments/assets/dd0a656d-4170-40b1-a3e4-f23336de4871" />


---

## Business Questions
This project was designed to answer questions such as:
- Which products and categories generate the most revenue?
- How do sales trends change over time?
- How does performance differ across regions or countries?
- Which segments underperform relative to the overall average?

---

## Dataset
The dataset represents a **simulated retail / coffee sales dataset** commonly used in business analytics case studies.  
It includes transactional sales records with product, date, pricing, and geographic attributes.

---

## Tools & Techniques Used

### Data Preparation
- Converted raw ranges into structured Excel Tables
- Removed duplicates and handled missing values
- Standardized date, category, and numeric formats

### Formulas & Data Transformation
- **XLOOKUP** and **INDEX + MATCH** to enrich and relate data
- **IF logic** to create calculated fields and classifications
- Derived metrics such as total sales and category-level summaries

### Analysis & Visualization
- **PivotTables** to summarize sales by product, region, and time
- **PivotCharts** for visual comparison of trends
- **Slicers and Timelines** to enable dynamic filtering and interactivity

---

## Dashboard Features
The final dashboard allows users to:
- Filter sales by product type and country
- Analyze trends over time using a timeline control
- Compare performance across categories and regions
- View key KPIs in a single, consolidated layout

The layout prioritizes clarity and usability, making it suitable for quick decision-making rather than static reporting.

---

## Key Insights
Some high level insights from the analysis include:
- A small subset of products contributes a disproportionate share of total revenue
- Sales display clear seasonal patterns over time
- Certain regions underperform despite similar order volumes, indicating potential pricing or product mix issues

---

## Recommendations
Based on the analysis:
- Focus inventory and marketing efforts on high performing products
- Re-evaluate pricing or discount strategies in underperforming regions
- Align operational planning with observed seasonal demand patterns

---

## Files in This Repository
- `sales_dashboard.xlsx` — Interactive Excel dashboard with KPIs, charts, slicers, and timeline
- `raw_data.xlsx` — Dataset used for analysis
- `images/` — Screenshots of raw data and the final dashboard

---

## What I’d Improve Next
With additional time, I would:
- Automate data refresh using Power Query
- Connect the dashboard to a SQL database for scalability
- Add profitability and margin analysis alongside revenue metrics
