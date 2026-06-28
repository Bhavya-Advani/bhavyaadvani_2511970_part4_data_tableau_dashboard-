


# 1. Sales Trend View

| Design Aspect                | Explanation                                                                                                                                                           |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Question**        | How have sales changed over time based on the order date?                                                                                                             |
| **Chart Type Used**          | Line Chart                                                                                                                                                            |
| **Why This Chart?**          | A line chart is the most appropriate visualization for displaying trends over time because it clearly shows increases, decreases, and seasonal fluctuations in sales. |
| **Fields Used**              | **X-axis:** Order Date (Month/Year)<br>**Y-axis:** Total Sales<br>**Filter:** Order Date, Region, Category                                                            |
| **Design Principle Applied** | Chronological ordering allows leadership to quickly identify trends and seasonal patterns.                                                                            |
| **Mistake Avoided**          | Avoided using a bar chart for time-series data, which would make trend identification less intuitive.                                                                 |

---

# 2. Regional Performance View

| Design Aspect                | Explanation                                                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Business Question**        | Which regions generate the highest sales and profit?                                                                        |
| **Chart Type Used**          | Comparative Bar Chart                                                                                                       |
| **Why This Chart?**          | Bar charts provide a clear comparison of values across discrete categories, making it easy to compare regional performance. |
| **Fields Used**              | **Category:** Region<br>**Measures:** Sales and Profit<br>**Color:** Sales vs Profit                                        |
| **Design Principle Applied** | Direct side-by-side comparison enables rapid identification of high- and low-performing regions.                            |
| **Mistake Avoided**          | Avoided using a pie chart because precise comparison between regions is easier with bars.                                   |

---

# 3. Category Profitability View

| Design Aspect                | Explanation                                                                                                                      |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Business Question**        | Which product categories and sub-categories contribute the most to sales and profit?                                             |
| **Chart Type Used**          | Pivot Table / Matrix                                                                                                             |
| **Why This Chart?**          | A pivot table efficiently summarizes hierarchical data, allowing users to compare categories and drill down into sub-categories. |
| **Fields Used**              | **Rows:** Category, Sub-Category<br>**Values:** Sales, Profit                                                                    |
| **Design Principle Applied** | Hierarchical organization improves readability and supports detailed analysis.                                                   |
| **Mistake Avoided**          | Avoided overcrowding the dashboard with multiple individual charts for each category.                                            |

---

# 4. Customer Segment View

| Design Aspect                | Explanation                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------ |
| **Business Question**        | Which customer segments generate the highest sales and profit?                                   |
| **Chart Type Used**          | Bar Chart                                                                                        |
| **Why This Chart?**          | Bar charts effectively compare performance across a small number of customer segments.           |
| **Fields Used**              | **Category:** Customer Segment<br>**Measure:** Sales (and Profit)<br>**Color:** Customer Segment |
| **Design Principle Applied** | Simple categorical comparison emphasizes differences between customer groups.                    |
| **Mistake Avoided**          | Avoided stacked charts that would make comparisons more difficult.                               |

---

# 5. Shipping Performance View

| Design Aspect                | Explanation                                                                                               |
| ---------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Business Question**        | How does shipping mode relate to delivery delay?                                                          |
| **Chart Type Used**          | Bar Chart (Average Delivery Delay by Ship Mode)                                                           |
| **Why This Chart?**          | A bar chart clearly compares average shipping delays across different shipping methods.                   |
| **Fields Used**              | **Category:** Ship Mode<br>**Measure:** Average Shipping Delay (Days)<br>**Filter:** Region, Order Status |
| **Design Principle Applied** | Consistent scales make operational differences easy to interpret.                                         |
| **Mistake Avoided**          | Avoided using a line chart because ship modes are categorical rather than chronological.                  |

---

# 6. Discount vs Profit View

| Design Aspect                | Explanation                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **Business Question**        | What is the relationship between discounts and profitability?                                                                      |
| **Chart Type Used**          | Scatter Plot                                                                                                                       |
| **Why This Chart?**          | Scatter plots are ideal for exploring relationships between two continuous numerical variables and identifying trends or outliers. |
| **Fields Used**              | **X-axis:** Discount (%)<br>**Y-axis:** Profit<br>**Color:** Category<br>**Size:** Sales (optional)                                |
| **Design Principle Applied** | Individual points reveal patterns, clusters, and outliers that may not be visible in summary statistics.                           |
| **Mistake Avoided**          | Avoided summarizing the data with averages, which could hide important variability.                                                |

---

# 7. Return Analysis View

| Design Aspect                | Explanation                                                                                                |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Business Question**        | Which categories, customer segments, or regions experience the highest return rates?                       |
| **Chart Type Used**          | Bar Chart                                                                                                  |
| **Why This Chart?**          | Bar charts provide a straightforward comparison of return volumes across categories, segments, or regions. |
| **Fields Used**              | **Category:** Category / Segment / Region<br>**Measure:** Return Count<br>**Color:** Return Status         |
| **Design Principle Applied** | Consistent sorting highlights the highest return areas for management attention.                           |
| **Mistake Avoided**          | Avoided pie charts because ranking and comparison are easier to interpret with bars.                       |

---

# Overall Dashboard Design Principles

The dashboard was developed using the following design principles:

* **Executive-focused:** Displays the most important business KPIs without unnecessary complexity.
* **Consistency:** Similar chart styles, fonts, and colors are used throughout the dashboard.
* **Clear comparisons:** Appropriate chart types were selected based on the type of business question.
* **Minimal clutter:** Only essential information is displayed to maximize readability.
* **Interactive analysis:** Filters allow users to explore performance by region, category, customer segment, and time period.
* **Visual hierarchy:** The most important KPIs and trends are positioned prominently to guide the viewer through the business story.

These design choices ensure that the dashboard supports quick, evidence-based decision-making while remaining easy to interpret for senior leadership.
