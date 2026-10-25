# retail-sales-intelligence
Retail sales and profitability analysis using SQL, Python, and Power BI


## Business Problem

Retail businesses need to understand not only how much they sell, but also where they earn or lose profit. This project explores the Sample Superstore dataset to identify performance patterns and support better-informed business decisions.

## Questions Explored

- What are the overall sales, profit, order count, and profit margin?
- Which categories and sub-categories contribute most to profit?
- Which products or sub-categories generate losses?
- How are discounts associated with profitability?
- How do sales and profit vary across regions and over time?
- Which customers contribute the most sales and profit?
- How do shipping methods relate to delivery time and profitability?

## Tools Used

- **Python:** Pandas, NumPy, Matplotlib, Jupyter Notebook
- **Database and querying:** MySQL, SQL
- **Visualization:** Power BI, DAX, KPI cards, interactive filters
- **Data files:** CSV

## Dataset

The project uses the Sample Superstore dataset. The existing project documentation describes 9,994 records covering orders, customers, products, sales, quantity, discounts, profit, regions, and shipping. Verify the dataset dimensions and column names in the included CSV before relying on them in a presentation or interview.

## Analysis Workflow

1. **Prepare the data:** inspect data types, check duplicates, convert order and ship dates, and derive useful fields where appropriate.
2. **Explore patterns with Python:** examine category, sub-category, discount, customer, regional, and time-based performance.
3. **Query with SQL:** calculate business metrics and compare performance across products, customers, regions, and periods.
4. **Visualize with Power BI:** present key metrics and trends in an interactive report.
5. **Communicate findings:** validate the calculations and document evidence-based observations and recommendations.

## Files in This Repository

```text
retail-sales-intelligence/
├── Superstore_Cleaned.csv
├── Superstore_Dashboard.pbix
├── superstore_analysis.sql
├── superstore_data_analysis.ipynb
├── README.md
├── LICENSE
└── .gitignore
```

## How to Explore the Project

1. Review `Superstore_Cleaned.csv` to understand the available fields.
2. Open `superstore_data_analysis.ipynb` in Jupyter Notebook to inspect the Python analysis.
3. Review `superstore_analysis.sql` to understand the SQL queries.
4. Open `Superstore_Dashboard.pbix` in Power BI Desktop to explore the report.

File names and analysis steps may need adjustment if the project files change.

## Findings to Validate

The source project documentation reports the following observations. Re-run the calculations in the included files before treating these as verified results:

- Reported total sales: approximately **$2.30 million**.
- Reported total profit: approximately **$286.40 thousand**.
- Reported overall profit margin: approximately **12.47%**.
- Technology is reported as the highest-profit main category.
- Furniture is reported as less profitable than Technology and Office Supplies.
- Tables and Bookcases are reported among the loss-making sub-categories.
- Higher discount levels are reported as being associated with lower average profitability.

These are descriptive observations, not proof that discounts caused lower profits.

## Next Improvements

Planned improvements for this portfolio version:

- Verify all metrics against the CSV and SQL outputs.
- Add screenshots of the dashboard after checking the report.
- Document original findings and recommendations in my own words.
- Add further SQL analysis and clearly describe the changes made in this repository.

## Source and License

This repository adapts work from the original project:

**Original repository:** https://github.com/Akhil-Sheelam/superstore-sales-profitability-analysis

The original MIT license and required copyright and license notices are retained in `LICENSE`. Please review that file for the applicable terms and preserve required notices when redistributing this project.

---

**Portfolio note:** This repository should be described as an adapted project until independent analysis and meaningful customizations have been completed and can be explained confidently.
