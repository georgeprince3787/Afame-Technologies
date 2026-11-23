# Sales Data Analysis

## Organization

AFAME Technologies - Data Analyst Internship Project

## Objective

Analyze order-level sales records to identify revenue patterns, profitable products, customer contribution, regional performance, shipping behavior, and discount relationships.

## Dataset

The original source workbook is [ECOMM DATA.xlsx](../ECOMM%20DATA.xlsx). The notebook reads the `Orders` sheet. The workbook's `Returns` and `People` sheets are reference sheets and are not substituted for the order-level analysis.

## Notebook

Open [Sales_Data_Analysis.ipynb](notebooks/Sales_Data_Analysis.ipynb).

## Analysis Included

- Workbook and sheet validation
- Missing values, duplicates, dates, quantities, discounts, and text quality checks
- Separate cleaned DataFrame
- Time features and profitability features
- Sales, profit, order, discount, shipping, and AOV KPIs
- Year, month, quarter, and year-month trends
- Product, category, sub-category, customer, segment, country, region, and state analysis
- Shipping mode, priority, discount, correlation, and outlier analysis
- Business insights and realistic recommendations
- Cleaned data and summary CSV exports
- Saved PNG charts

## Main Results

- Total sales: $12,642,501.91
- Total profit: $1,467,457.29
- Unique orders: 25,035
- Top product by sales: Apple Smart Phone, Full Size
- Largest region by sales: Central

## Outputs

- [cleaned_sales_data.csv](outputs/cleaned_sales_data.csv)
- [Summary CSV files](outputs/)
- [Chart images](outputs/charts/)

## Run

From the project root:

```cmd
python -m pip install -r requirements.txt
python -m jupyter notebook
```

Open the notebook and run **Restart & Run All**.
