# Global Superstore — Executive BI Dashboard
**Business Intelligence & Interactive Dashboard Development — AnalystLab Africa Data Analytics Internship, Week 2**

An executive Power BI dashboard built as a Junior Business Intelligence Analyst at AnalystLab Africa Consulting, commissioned by a national retail company to monitor sales performance, profitability, customer behavior, and regional performance.

## Business Scenario

Senior management needed an interactive dashboard that transforms raw transactional data into decisions they could act on directly — without waiting on a new report every time a question came up. This project covers data preparation, dashboard design, and business recommendations end to end.

## Business Questions

1. What is the overall sales performance of the company?
2. Which regions generate the highest sales and profit?
3. Which customer segments contribute the most revenue?
4. Which product categories perform best?
5. Which products are the most profitable?
6. What trends can be observed over time?
7. What recommendations should management implement to improve business performance?

## Headline Findings

| Metric | Value |
|---|---|
| Total Sales | $12,642,501.91 |
| Total Profit | $1,467,457.29 |
| Overall Profit Margin | 11.6% |
| Total Orders | 25,035 |
| Period Covered | 2011 – 2014 |

- **Growth**: Sales nearly doubled year over year, from $2.26M (2011) to $4.30M (2014), with no down years.
- **Regional efficiency gap**: Canada is the smallest market by sales ($66,928) but the most profitable by margin (26.6%) — more than double the company average.
- **Hidden loss**: The Tables sub-category is the only one in the entire dataset generating a net loss (~-$64,000), masked inside an otherwise healthy Furniture category.
- **Margin risk**: Southeast Asia ($884K sales) and EMEA ($806K sales) both convert substantial revenue into unusually thin profit (2.0% and 5.4% margin respectively).

Full detail, insights, risks, opportunities, and recommendations are in the Executive Summary Report below.

## Dashboard

Built in Microsoft Power BI. Includes:
- 5 KPI cards (Total Sales, Total Profit, Total Orders, Average Sales, Profit Margin)
- 8 visualizations: 2 bar charts, 2 column charts, 1 line chart, 1 donut chart, 1 map, 1 matrix
- 2 interactive slicers (Order Year, Market)

## Repository Structure

```
├── dashboard/
│   ├── Global_Superstore_Dashboard.pbix     # Power BI project file
│   └── Global_Superstore_Dashboard.pdf      # Exported dashboard view
├── reports/
│   ├── 01_BI_Overview_Report.docx
│   └── 02_Executive_Summary_Report.docx
├── data/
│   └── Global_Superstore_Clean.csv          # Cleaned dataset used in the dashboard
└── README.md
```

## Dataset

[Global Superstore Dataset](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset) — 51,290 order line items across 147 countries, 2011–2014.

## Tools & Skills Applied

Microsoft Power BI (Power Query, DAX, data modeling, interactive dashboards) · Data Cleaning & Transformation · KPI Design · Business Insight Generation · Executive Reporting

## Author

**Oluwatosin Olusanya**
Data Analytics Intern, AnalystLab Africa
Senior Finance Officer (13+ years) transitioning into Financial Data Analysis
[LinkedIn](https://www.linkedin.com/in/PLACEHOLDER) · [X / Twitter](https://x.com/PLACEHOLDER)

## Acknowledgment

Completed as part of the [AnalystLab Africa](https://www.analystlabafrica.com) Data Analytics Internship Programme — building Africa's next generation of Data, AI & Technology professionals.
