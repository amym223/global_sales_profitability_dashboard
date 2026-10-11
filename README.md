# Global Sales & Profitability Analysis Dashboard

An interactive, three page *Microsoft Power BI* dashboard exploring sales, costs, discounts, and profitability across products, countries, customer segments, and time periods.

# Project Overview

This project turns financial sample data into an interactive report for exploring business performance from several perspectives:

- *Overall Performance* — headline KPIs, quarterly profit, sales by segment, units sold by product, and transactions by discount band.
- *Product & Geographic Performance* — profit by country and product, plus discount patterns across products and markets.
- *Segment Performance* — monthly sales, quarterly profit by segment, and profit margin by customer segment.

The goal is to demonstrate how business intelligence can help users move from highl evel performance monitoring to more detailed analysis and evidence informed follow up questions.

# Business Questions

The dashboard was designed to help investigate questions such as:

- What are the overall sales, costs, profit, and profit margin?
- How does profitability differ across countries and products?
- Which customer segments contribute most to sales, and which show stronger margins?
- How do discount values vary across products and markets?
- How does performance change by month and quarter?
- Which results warrant further investigation?

# Tools & Skills

- *Microsoft Power BI* — report design, KPI cards, visualizations, slicers, and interactive exploration
- *DAX (Data Analysis Expressions)* — reusable measures for financial and operational metrics
- *Data analysis* — sales, cost, discount, profit, product, geographic, segment, and trend analysis
- *Data visualization* — organizing findings into a clear, three page analytical narrative
- *Business thinking* — translating observed patterns into recommendations and follow up questions

# Dataset & Measures

The report uses the Microsoft Financials sample data as identified during project development. The visuals cover products, countries, customer segments, discount bands, and time periods. 

# DAX measures created

- Average Manufacturing Price
- Average Sale Price
- Discounts (%)
- Profit Margin (%)
- Total COGS
- Total Discounts
- Total Gross Sales
- Total Profit
- Total Sales
- Total Units Sold

These measures support the dashboard's financial KPIs and comparisons

# Headline Results

The current dashboard displays the following overall figures:

| KPI | Displayed result |

| Total Sales | $118.73M |
| Total COGS | $101.83M |
| Total Profit | $16.89M |
| Profit Margin | 14.23% |
| Total Discounts | $9.21M |
| Total Units Sold | 1.13M |


# Key Findings

The current report highlights several patterns for further investigation:

1. *Government is the largest sales segment* in the displayed analysis, at approximately $53M.
2. *Channel Partners show the highest displayed segment profit margin* (73.13%), while Enterprise shows a negative displayed margin (-3.13%).
3. *France shows the highest displayed total profit by country*, at approximately $3.8M.
4. *Paseo is the highest-volume product* in the displayed report and also has the highest total discount value.
5. *October has the highest monthly sales value shown*, at approximately $22M.

# Recommendations for Further Analysis

- Investigate the drivers of the negative displayed Enterprise margin, including costs, pricing, product mix, and discounts.
- Compare discount levels with sales and profit to evaluate discount effectiveness.
- Examine the product, pricing, and cost mix behind the Channel Partners margin.
- Compare stronger and weaker geographic markets to identify differences worth exploring.
- Evaluate whether Paseo's discount exposure is justified by its sales and profit contribution.
- Investigate the products, markets, and segments contributing to the October sales peak.

# Dashboard Pages

# 1. Overall Performance
A high level view of sales, COGS, profit, margin, discounts, units sold, quarterly profit, sales by segment, and product volume.

# 2. Product & Geographic Performance
A comparison of profit across countries and products, alongside discount patterns by product and country.

# 3. Segment Performance
A view of monthly sales, quarterly profit by segment, and profit margins across customer segments.

# Repository Contents

    global_sales_profitability_dashboard/
├── README.md
├── screenshots/
│   ├── overall_performance.png
│   ├── product_geographic_performance.png
│   └── segment_performance.png
├── report/
│   └── portfolio_case_study.pdf
└── powerbi/
    └── global_sales_profitability_dashboard.pbix

# How to View

1. Open the screenshots in the `screenshots/` folder for a quick overview.
2. Read the PDF case study in the `report/` folder for the project context, analysis, findings, and recommendations.
3. Open `.pbix/` file with Microsoft Power BI Desktop to explore the report interactively.


# Author - Amy Munjoma

Created as a data analytics portfolio project to demonstrate Power BI dashboard development, DAX measures, financial analysis, and business insight generation.
