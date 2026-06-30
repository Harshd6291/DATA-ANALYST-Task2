# Task 2: Data Visualization and Storytelling

**Internship:** Data Analyst Internship – Elevate Labs
**Task:** Task 2 – Data Visualization and Storytelling
**Tool Used:** Tableau Public
**Dataset:** Sample Superstore.csv (sales data)

## Objective

Create visualizations that convey a compelling business story using the Superstore sales dataset, focusing on clear chart choice, minimal clutter, and actionable insights rather than just visuals.

## Dataset Overview

The dataset contains 9,994 records of retail orders with details on Sales, Profit, Discount, Quantity, Category, Sub-Category, Region, Segment, and Order Date (2014–2017).

## Key Business Insights

- **Total Sales:** $2.30M
- **Total Profit:** $286K
- **Overall Profit Margin:** 12.5%
- Sales and profit grew every year from 2014 to 2017, but profit growth lagged behind sales growth, indicating shrinking margins over time.
- **Tables (-$17.7K)** and **Bookcases (-$3.5K)** are the only sub-categories operating at a net loss, despite Tables alone generating $207K in sales.
- Discount level is **negatively correlated with profit** (correlation: -0.22) — heavier discounting is directly eating into margins, especially within the Furniture category.
- **Technology** is the most profitable category ($145K profit) despite having similar sales volume to Furniture ($836K vs $742K), which earns roughly 8x less profit.
- **West** ($108K profit) and **East** ($92K profit) regions are the strongest performers; **Central** is the weakest ($40K profit).
- **Consumer** segment drives the most sales ($1.16M) and profit ($134K) of the three customer segments.

## Dashboard Contents

The Tableau dashboard includes the following visualizations:

1. **KPI Tiles** – Total Sales, Total Profit, and Profit Margin (%) as headline numbers.
2. **Sales vs Profit by Year (Line Chart)** – Shows sales growing faster than profit, highlighting margin compression.
3. **Profit by Sub-Category (Sorted Bar Chart)** – Highlights Tables and Bookcases as loss-making sub-categories, color-coded red (loss) to blue (profit).
4. **Discount vs Profit (Scatter Plot)** – Shows the relationship between discounting and profitability, colored by Category.
5. **Sales by State (Map)** – Geographic breakdown of sales performance across the U.S.

An annotation on the Profit by Sub-Category chart calls out the key takeaway: *"Tables lose money despite high sales — review discounting."*

## Key Takeaway / Recommendation

While overall sales and profit are growing year over year, the business is leaving money on the table in the Furniture category. Tables and Bookcases should have discount caps reviewed or repriced, since heavier discounts are directly correlated with shrinking profit. Doubling down on Technology and the West/East regions, which already deliver the strongest margins, is likely to be more profitable than further discount-driven sales pushes in Furniture.

## Files in This Repository

- `Sample__Superstore.csv` – Source dataset
- `superstore_dashboard.twbx` – Tableau Public packaged workbook (or link below)
- `dashboard_screenshot.png` – Exported dashboard image
- `visual_report.pdf` – Final visual report / storyboard
- `README.md` – This file

## Tools Used

Tableau Public (free version) for data visualization and dashboard design.
