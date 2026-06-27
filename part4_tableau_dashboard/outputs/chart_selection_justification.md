# Sales Trend View

**Business question:**
How have sales evolved over time?

**Chart type:**
Line chart

**Why this chart:**
Line charts best show temporal changes and trends, helping leadership spot growth, declines, and seasonal patterns quickly.

**Fields used:**

* X-axis: Order date (Month/Year)
* Y-axis: Sales
* Filters: Date, Region, Category, Customer segment

**Design principle:**
A straightforward chronological layout with a single metric emphasizes long-term trends and keeps the view easy to read.

**Mistake avoided:**
A bar chart was not used because it becomes crowded for continuous time-series data.

---

# Regional Performance View

**Business question:**
Which regions deliver the most sales and profit?

**Chart type:**
Horizontal bar chart

**Why this chart:**
Horizontal bars make cross-region comparisons simple and allow quick identification of top and bottom performers.

**Fields used:**

* Category: Region
* Measure: Sales and Profit
* Color: Profit
* Filters: Date, Category, Customer segment

**Design principle:**
Sorting bars by performance helps efficient comparison, while color highlights profitability.

**Mistake avoided:**
Pie charts were skipped because they make it hard to compare multiple regions.

---

# Category Profitability View

**Business question:**
Which product categories and sub-categories drive the most profit?

**Chart type:**
Bar chart

**Why this chart:**
Bars give a clear side-by-side comparison of profitability across categories and sub-categories, revealing strong and weak areas.

**Fields used:**

* Category: Category and Sub-Category
* Measure: Profit
* Color: Profit
* Filters: Region, Date

**Design principle:**
Uniform colors and sorted ordering enhance readability and draw attention to the most profitable categories.

**Mistake avoided:**
Treemaps were avoided since exact profit comparisons are easier with bar charts.

---

# Customer Segment View

**Business question:**
How do customer segments perform relative to one another?

**Chart type:**
Bar chart

**Why this chart:**
Bar charts provide a direct comparison of sales and profit across customer segments.

**Fields used:**

* Category: Customer segment
* Measure: Sales and Profit
* Color: Customer segment
* Filters: Region, Date

**Design principle:**
Distinct colors differentiate segments while keeping the layout neat and uncluttered.

**Mistake avoided:**
3D charts were excluded because they harm readability and can distort comparisons.

---

# Shipping Performance View

**Business question:**
How do shipping options and delivery delays impact operations?

**Chart type:**
Bar chart

**Why this chart:**
Bars clearly compare shipping modes and delay categories, helping point out logistics issues that need attention.

**Fields used:**

* Category: Ship mode
* Measure: Delivery days / Order count
* Color: Shipping delay bucket
* Filters: Region, Date

**Design principle:**
Color coding separates delay categories; the clean layout enables quick comparisons across shipping methods.

**Mistake avoided:**
Complex stacked visuals were avoided to keep operational metrics easy to interpret.

---

# Discount vs Profit View

**Business question:**
What relationship exists between discounts and profitability?

**Chart type:**
Scatter plot

**Why this chart:**
Scatter plots are ideal for exploring relationships between two continuous measures and spotting patterns or outliers.

**Fields used:**

* X-axis: Discount
* Y-axis: Profit
* Color: Category
* Filters: Region, Customer segment

**Design principle:**
The scatter plot reduces clutter and makes trends and anomalies straightforward to spot.

**Mistake avoided:**
Line charts were not used because discounts are not sequential time-series data.

---

# Return Analysis View

**Business question:**
Which products, segments, or regions have higher return rates?

**Chart type:**
Bar chart

**Why this chart:**
Bar charts offer an easy comparison of return counts across dimensions and highlight areas that need investigation.

**Fields used:**

* Category: Category / Region / Customer segment
* Measure: Return count
* Color: Return status
* Filters: Region, Date

**Design principle:**
Consistent formatting and sorted values make high-return areas immediately apparent to stakeholders.

**Mistake avoided:**
Decorative charts were avoided because they reduce analytical clarity and complicate comparisons.

---

# Overall dashboard design principles

The executive dashboard focuses on delivering a clear, interactive, and business-oriented snapshot for leadership. It applies consistent color schemes, legible labels, concise KPI cards, interactive filters, and chart choices that match the business questions. Every visual was selected to answer a specific question while minimizing clutter and avoiding misleading chart types. The dashboard lets users drill into performance by region, customer segment, product category, shipping method, discount behavior, and returns using interactive filters and dashboard actions.
