# Global Superstore — Executive BI Dashboard
**Business Intelligence & Interactive Dashboard Development — AnalystLab Africa Data Analytics Internship**

An executive Power BI dashboard built as a Data Analyst at AnalystLab Africa Consulting, commissioned by a national retail company to monitor sales performance, profitability, customer behavior, and regional performance — extended in Week 3 into deeper diagnostic analysis of *why* specific patterns occur and what management should do about them.

## Business Scenario

Senior management needed an interactive dashboard that transforms raw transactional data into decisions they could act on directly. Week 2 delivered the first version of that dashboard. Week 3 extends it with advanced analysis, additional KPIs and DAX measures, time-based trends, and root-cause investigation of three business problems.

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
| Total Customers | ~1,590 |
| Average Discount | 14.3% |
| Period Covered | 2011 – 2014 |

**Week 2 findings:**
- Sales nearly doubled year over year, from $2.26M (2011) to $4.30M (2014), with no down years.
- Canada is the smallest market by sales but the most profitable by margin (26.6%).
- The Tables sub-category was the only one generating a net loss company-wide.

**Week 3 findings (the "why" behind Week 2's patterns):**
- **Discount is the strongest destructive pattern in the dataset.** Profit margin falls in a near-perfect staircase as discount rises — from 25.3% at 0% discount to -111% at 51%+ discount (correlation r = -0.847). Orders discounted above 20% collectively lost $814,683.
- **Losses extend well beyond Tables.** Dozens of individual products across every category carry negative net profit, totaling roughly $920,646.
- **Southeast Asia's problem is really a Furniture problem.** Its Furniture margin is negative (-2.3%), while Office Supplies (1.7%) and Technology (6.4%) in the same region are merely thin, not loss-making.
- **Q4 is a reliable, repeatable seasonal peak** every year, with November and December consistently the strongest months.

Full detail, insights, risks, opportunities, and recommendations are in the reports below.

## Dashboard

Built in Microsoft Power BI, 2 pages:

**Page 1 — Executive Dashboard (Week 2):** 5 KPI cards, 8 visualizations (bar, column, line, donut, map, matrix), 2 slicers.

**Page 2 — Advanced Analysis (Week 3):** 6 KPI cards, quarterly/yearly trend chart, discount-band profit margin chart, sub-category and regional margin charts, loss-making products table, 3 slicers (Year, Region, Category).

**10 DAX measures + 1 calculated column** across both pages — full documentation in `reports/04_DAX_Measures_Documentation.docx`.

## Repository Structure

```
├── dashboard/
│   ├── Global_Superstore_Dashboard.pbix     # Power BI project file (both pages)
│   └── Global_Superstore_Dashboard.pdf      # Exported dashboard, both pages
├── reports/
│   ├── 01_BI_Overview_Report.docx                       # Week 2
│   ├── 02_Executive_Summary_Report.docx                 # Week 2
│   ├── 01_Project_Continuity_Summary.docx               # Week 3
│   ├── 02_Advanced_Data_Analysis_Report.docx            # Week 3
│   ├── 03_Business_Insights_and_Recommendations_Report.docx  # Week 3
│   └── 04_DAX_Measures_Documentation.docx               # Week 3
├── data/
│   └── Global_Superstore_Clean.csv          # Cleaned dataset used throughout
└── README.md
```

## Dataset

[Global Superstore Dataset](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset) — 51,290 order line items across 147 countries, 2011–2014. Same dataset used continuously across Weeks 2 and 3, per assignment requirements.

## Tools & Skills Applied

Microsoft Power BI (Power Query, DAX, data modeling, interactive dashboards) · Advanced Business Analysis · Time-Series Analysis · Discount/Pricing Impact Analysis · KPI Design · Business Insight Generation · Executive Reporting

## Author

**Oluwatosin Olusanya**
Data Analytics Intern, AnalystLab Africa
Senior Finance Officer (13+ years) transitioning into Financial Data Analysis
[LinkedIn](https://www.linkedin.com/in/PLACEHOLDER) · [X / Twitter](https://x.com/PLACEHOLDER)

## Acknowledgment

Completed as part of the [AnalystLab Africa](https://www.analystlabafrica.com) Data Analytics Internship Programme — building Africa's next generation of Data, AI & Technology professionals.
