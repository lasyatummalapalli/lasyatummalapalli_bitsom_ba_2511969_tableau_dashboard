Executive Dashboard for Retail Sales Analysis using Tableau

This repository contains the Tableau Executive Dashboard developed for Part 4 of the Business Analytics assignment. It includes the Tableau packaged workbook, source dataset, dashboard documentation, screenshots, and supporting analysis.

Business problem overview
Retail executives need a single, centralized dashboard to track core performance metrics, surface operational risks, and guide strategic decisions. This work analyzes transactional retail sales data in Tableau to deliver insights on sales patterns, profitability, regional outcomes, customer segments, shipping efficiency, discount effects, and return behavior.

Dataset details
This project uses the dashboard_sales_data.xlsx file supplied for Part 4. The dataset contains transaction-level retail fields, including:

Order Date

Ship Date

Region

State

Category

Sub-Category

Customer Segment

Ship Mode

Sales

Profit

Discount

Quantity

Delivery Days

Return Flag

The data was loaded into Tableau for visualization and analysis.

Tableau workbook
The packaged Tableau workbook (executive_dashboard.twbx) delivers an interactive executive dashboard supported by several worksheets. The dashboard lets leadership explore sales and profitability trends, customer and regional performance, logistics metrics, and return patterns via interactive charts and filters.

Calculated fields
The following calculated fields were created in Tableau:

Profit Margin = Profit / Sales

Cost = Sales − Profit

Average Order Value = Sales / Number of Orders

Return Rate = Returned Orders / Total Orders

Shipping Delay Bucket = Bucketized delivery days into meaningful delay categories

These fields extend the original data with business-relevant metrics.

Dashboard elements
The executive dashboard contains these visual components:

Sales Trend View

Regional Performance View

Category Profitability View

Customer Segment View

Shipping Performance View

Discount vs Profit View

Return Analysis View

It also includes KPI cards that show:

Total Sales

Total Profit

Profit Margin

Filters and interactions
Interactive filters available on the dashboard include:

Region

Category

Customer Segment

Date

Ship Mode

Dashboard actions let users filter multiple charts at once for deeper, cross-cutting analysis.

Key business findings
The dashboard surfaces several important observations:

Sales show relative stability with occasional upticks over time.

Performance differs substantially by region.

Profitability varies widely across product categories.

Customer segments contribute unevenly to sales and profit.

Larger discounts often correspond with lower profitability.

Shipping performance differs by ship mode.

Returns are concentrated in particular product or business areas.

Operational improvements can boost profitability without simply increasing sales.

Dashboard narrative
The dashboard integrates sales, profitability, customer, regional, shipping, discount, and return analyses into a single executive view. Rather than presenting isolated numbers, it links multiple business dimensions so leadership can spot strengths, weaknesses, risks, and growth possibilities. Interactive filters and focused visualizations support data-driven decision-making.

Assumptions and limitations
Assumptions

The dataset provided is complete and accurate.

Delivery Days correctly reflect shipping time.

Return Flag properly marks returned orders.

Profit values in the dataset are correct.

Limitations

The dashboard is based on historical data only and does not produce forecasts.

External influences (customer satisfaction, marketing actions, competitor pricing, inventory availability, seasonality, etc.) are not included.

Conclusions are bounded by the scope and quality of the supplied dataset.

Included screenshots
The repository includes these dashboard images:

full_dashboard.png

sales_trend_view.png

regional_performance_view.png

category_profitability_view.png

filter_interaction_view.png

Repository structure
part4_tableau_dashboard/
├── data/
│ └── dashboard_sales_data.xlsx
├── tableau/
│ └── executive_dashboard.twbx
├── outputs/
│ ├── dashboard_story.md
│ ├── business_insights.md
│ └── chart_selection_justification.md
├── screenshots/
│ ├── full_dashboard.png
│ ├── sales_trend_view.png
│ ├── regional_performance_view.png
│ ├── category_profitability_view.png
│ └── filter_interaction_view.png
└── README.md

Conclusion
This Tableau executive dashboard converts raw retail transaction data into an interactive business intelligence tool for leadership. By combining key KPIs, multiple analytical views, calculated measures, and interactive filters, the dashboard helps executives monitor performance, detect operational risks, and find opportunities to improve results.