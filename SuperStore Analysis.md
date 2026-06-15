# Superstore Profitability Analysis

## Project Goal

The goal of this project is to analyze the Sample Superstore dataset to identify key drivers of profitability, uncover loss-making segments, and provide actionable business recommendations. The analysis focuses on product categories, regional performance, discount impact, and seasonal sales trends.

## Dataset Source

The dataset is the **Sample Superstore** dataset from Tableau, containing 9,994 rows and 21 columns. It includes sales, profit, discount, customer and geographic data for a retail store. The data was loaded and cleaned in Python using Pandas.

## Key Findings (3 bullets)

1. **Technology generates the highest profit** among all product categories, while Furniture and Office Supplies show lower margins.

2. **Discounts above 25% lead to negative average profit** per order, with high discounts (>40%) consistently producing losses.

3. **Tables, Bookcases, and Supplies** are the only sub‑categories with negative total profit, making them candidates for pricing or sourcing review.

## Best Chart

Below is the **Profit by Product Sub‑Category** chart, which clearly shows the loss‑making sub‑categories (in red) and the most profitable ones (in green).

![Profit by subcategory](profit_by_subcategory.png)

## Additional Insights

- **Central region** has the lowest profit margin (7.9%) despite decent sales, while **West** has both the highest sales and strong margins.
- **Monthly sales trend** shows a clear peak in November–December (holiday season) and a trough in January–February.
- The analysis includes data cleaning, type conversion, and feature engineering (profit margin, order year/month, discount bins).

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
