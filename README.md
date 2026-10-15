# Store Sales & Profit Analysis (Python)

An exploratory data analysis of store sales and profit, done in a Jupyter Notebook with Python. The analysis looks at how sales and profit change across **time, product categories, sub-categories and customer segments**, to find what drives revenue and where money is being lost.

## Tools Used

- Python
- Pandas, NumPy
- Matplotlib / Seaborn (visualizations)
- Jupyter Notebook

## Key Insights

### 1. Monthly Sales

| Metric | Month | Sales |
|---|---|---|
| Highest | November | 352.46K |
| Lowest | February | 59.75K |

### 2. Sales by Category

| Category | Share of Sales |
|---|---|
| Technology | 36.4% (highest) |
| Furniture | 32.3% |
| Office Supplies | 31.3% (lowest) |

### 3. Sales by Sub-Category

- **Highest:** Phones, about 330K in sales
- **Lowest:** Fasteners, 3,034 in sales

### 4. Monthly Profit

| Metric | Month | Profit |
|---|---|---|
| Highest | December | 43.36K |
| Lowest | January | 9,134 |

### 5. Profit by Category

| Category | Share of Profit |
|---|---|
| Technology | 50.8% (highest) |
| Office Supplies | 42.8% |
| Furniture | 6.44% (lowest) |

### 6. Profit by Sub-Category

- **Highest profit:** Copiers, 55.61K
- **Loss-making:** Tables, **-17.72K** (negative profit)

### 7. Customer Segments

| Segment | Sales-to-Profit Ratio | Equivalent Profit Margin |
|---|---|---|
| Consumer | 8.6 (highest) | about 11.6% |
| Corporate | 7.66 | about 13.1% |
| Home Office | 7.12 (lowest) | about 14.0% |

The ratio is sales divided by profit, meaning how much sales it takes to earn 1 of profit. A **lower ratio is better**, so Home Office is the most efficient segment and Consumer the least.

## Insights

1. **Strong seasonality:** November sales (352.46K) are about 5.9x February sales (59.75K). Profit follows a similar pattern, with December (43.36K) about 4.7x January (9,134).
2. **Sales do not always mean profit:**
   - Technology: 36.4% of sales gives 50.8% of profit.
   - Office Supplies: 31.3% of sales gives 42.8% of profit.
   - Furniture: 32.3% of sales gives only 6.44% of profit.
3. **Top seller is not the top earner:** Phones have the highest sales (about 330K), but Copiers have the highest profit (55.61K).
4. **Tables are the main problem:** with a loss of -17.72K, they pull down the whole Furniture category.
5. **Home Office is the most efficient segment:** it needs 7.12 of sales per 1 of profit (about 14.0% margin), while Consumer needs 8.6 (about 11.6% margin).
6. **Fasteners** sell very little (3,034), so they add almost nothing to revenue.

## Future Plan to Increase Profit

These are suggestions based on the insights above. Each one should be tested against the data before acting on it.

| Area | Problem found | Planned action |
|---|---|---|
| Tables / Furniture | Loss of -17.72K, Furniture profit only 6.44% | Check discount levels and costs for Tables; reduce discounts, adjust prices or drop the worst-performing items |
| Technology and Copiers | Biggest profit sources | Promote them more, and offer bundles such as Copiers with Office Supplies |
| Office Supplies | High profit share (42.8%) for its sales | Cross-sell with Technology orders to grow a high-margin category |
| Seasonality | Weak months: January and February | Run targeted offers in low months and plan stock and marketing ahead of November and December |
| Customer segments | Consumer has the highest sales-to-profit ratio (8.6), so the lowest profit per sale | Review discounts and costs on Consumer orders to improve margin, and look for ways to grow Home Office, the most efficient segment |
| Fasteners | Lowest sales (3,034) | Bundle with other Office Supplies or reduce stock held |

## How to Run

1. Clone this repository.
2. Install the requirements: `pip install pandas numpy matplotlib seaborn jupyter`
3. Open the notebook with `jupyter notebook` and run all cells.

## Author

**Tejas**
MCA Student | Aspiring Data Analyst
Portfolio: [tejasteke.github.io](https://tejasteke.github.io)
"# Ecommerce_analysis_python" 
