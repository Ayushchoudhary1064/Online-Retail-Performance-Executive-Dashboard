# 📊 Online Retail Performance: Executive Dashboard

## Project Summary
This project analyzes a transactional online retail dataset to provide key business intelligence for executive decision-making. The dashboard addresses specific requests from the CEO and CMO regarding revenue trends, high-value customers, top-performing countries, and future expansion opportunities.

**Technical Status:** All four required questions have been successfully visualized and filtered.

## Data Source
The report utilizes a transnational dataset containing all transactions from a UK-based non-store online retail business over a 13-month period (December 2010 to December 2011).

## Key Questions, Visuals, and Insights

The report is divided into three pages to address four key business questions:

### Page 1: Revenue Trends & Top Markets (Screenshots: image_42ff1f.png, image_41a14d.png)

This page provides an executive overview of overall business health.

| Question | Visual | Configuration & Insight |
| :--- | :--- | :--- |
| **Q1: 2011 Monthly Revenue Trend** | **Line Chart** | **Configuration:** X-axis is `Month`, Y-axis is `Sum of Revenue`. Filtered to show only 2011 data. **Insight:** Revenue shows clear, rapid growth throughout the year, peaking sharply in November and December. |
| **Q2: Top 10 Revenue-Generating Countries** | **Clustered Bar Chart** | **Configuration:** Top N filter applied to `Country` based on `Sum of Revenue`. **Insight:** The Netherlands is the top revenue generator outside the UK, highlighting a key international focus area. |

### Page 2: High-Value Customers (Screenshot: image_4301ce.png)

This page focuses on customer relationship management.

| Question | Visual | Configuration & Insight |
| :--- | :--- | :--- |
| **Q3: Top 10 Revenue-Generating Customers** | **Clustered Bar Chart** | **Configuration:** Top N filter applied to `CustomerID` based on `Sum of Revenue`. `CustomerID` is set to 'Don't Summarize'. **Insight:** Identifies the top 10 individual Customer IDs, allowing the sales team to focus on high-value client retention and loyalty programs. (e.g., Customer ID 12415 is a top contributor). |

### Page 3: Demand by Region (Screenshot: image_4301ee.jpg)

This map visual addresses strategic expansion and product demand.

| Question | Visual | Configuration & Insight |
| :--- | :--- | :--- |
| **Q4: Product Demand by Region** | **Map Visual** | **Configuration:** `Country` in **Location**, `Sum of Quantity` in **Bubble Size**. Filtered to **exclude** 'United Kingdom'. **Insight:** Visually identifies geographical areas with high product volume/demand (large bubbles) outside of the main UK market, indicating potential expansion sites. |

## Technical Skills Demonstrated

* **Data Modeling:** Calculated revenue and managed data granularity by ensuring `CustomerID` was treated as a distinct category ('Don't Summarize').
* **Filtering:** Applied three critical filtering techniques: **Date Filtering** (2011), **Top N Filtering** (Q2 and Q3), and **Exclusion Filtering** (excluding the UK in Q4).
* **Visual Selection:** Correctly matched visual types (Line, Bar, Map) to the objective (Trend, Ranking, Geospatial Analysis).
* **Report Design:** Implemented a **Dark Theme** for high visual contrast and readability across all pages, and applied professional titles.

## How to View the Report
1.  Download the **Online-Retail.pbix** file.
2.  Open the file using Power BI Desktop.

---