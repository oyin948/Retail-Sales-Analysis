# Retail Sales Analysis & Interactive Power BI Dashboard

## Project Overview

This project analyzes retail sales data to identify sales trends, product performance, customer patterns, and regional sales performance. The project involved cleaning and preparing the dataset with Python and building an interactive Power BI dashboard to explore the data and communicate key findings.

## Project Objectives

The main objectives of this project were to:

- Analyze overall retail sales performance
- Identify sales trends over time
- Examine product and sub-category performance
- Analyze customer and segment patterns
- Compare sales performance across regions
- Build an interactive dashboard to communicate insights

## Tools Used

- **Python** — Data validation, Data cleaning and preparation
- **Excel** — Data inspection and preliminary analysis
- **Power BI** — Data modeling, DAX, analysis, and visualization

## Dataset

The dataset contains **9,800 retail sales records and 18 columns** covering information about:

- Orders
- Customers
- Products
- Categories and sub-categories
- Dates
- Shipping methods
- Locations
- Sales

The dataset was cleaned and prepared before being used for analysis.

## Data Cleaning

Python was used to clean and prepare the dataset for analysis. The cleaning process included:

- Checking the dataset structure
- Inspecting data types
- Checking for missing values
- Inspecting for categorical values
- Checking for negative sales values
- Checking for missing postal codes
- Identifying potential numerical outliers
- Checking for duplicate records
- Converting date fields to appropriate date formats
- Checking numerical fields
- Preparing the dataset for Power BI analysis

No completely duplicate rows or negative sales values were identified. Potential sales outliers were identified using IQR method but retained because an unusually high sales value does not automatically indicate a data-entry error.

## Analysis Performed

**Sales Performance**
- Total sales
- Sales trends by year
- Sales by region
- Sales by category
- Sales growth over time

**Product Analysis**
- Sales by sub-category
- Top-performing products
- Sales contribution by sub-category
- Category and sub-category performance
- Product ranking

**Customer & Order Analysis**
- Number of unique customers
- Number of orders
- Average order value
- Sales by customer segment
- Orders by region
- Sales by shipping mode

## Power BI Dashboard

The Power BI report contains three main analysis pages:

### Page 1 — Sales Overview
Provides a high-level view of sales performance.

Key features include:
- Total Sales
- Total Orders
- Average Order Value
- Unique Customers
- Sales trend by year
- Sales by region
- Top 5 products by sales
- Sales by category
- Interactive slicers for Year, Region, and Category

![Sales Overview](screenshot/page1_overview.png)

### Page 2 — Product Analysis
Focuses on product and sub-category performance.

Key features include:
- Sales by sub-category
- Sales percentage by sub-category
- Category and sub-category breakdown
- Category sales trends
- Product-level sales details
- Product ranking

![Product Analysis](screenshot/page2_product_analysis.png)

### Page 3 — Customer & Order Analysis
Focuses on customer and order patterns.

Key features include:
- Unique customers
- Total orders
- Average order value
- Average sales per row
- Sales by customer segment
- Orders by region
- Customers by region
- Sales by shipping mode
- Customer and segment details

![Customer Analysis](screenshot/page3_customer_analysis.png)

## DAX & Data Modeling

DAX was used to create reusable measures and perform calculations such as:

- Total Sales
- Total Orders
- Average Order Value
- Unique Customers
- Unique Products
- Sales % of Total
- Sub-category Ranking
- Previous Year Sales
- Sales Growth %

A dedicated Date Table was also created and related to the sales data to support time-based analysis.

## Key Findings

- Technology generated the highest sales among the three major categories.
- Phones was the highest-selling sub-category.
- Sales increased substantially between 2016 and 2018 after a slight decline from 2015 to 2016.
- 2018 recorded the highest annual sales in the dataset.
- The fourth quarter recorded the highest quarterly sales in 2018.
- The dashboard allows users to explore these patterns interactively using slicers and filters.

## Skills Demonstrated

This project demonstrates practical experience with:

- Data cleaning with Python
- Data exploration
- Power Query
- Data modeling
- Relationships
- Date tables
- DAX
- Measures
- Time intelligence
- RANKX
- Top-N analysis
- Hierarchies
- Drill-down and drill-up
- Slicers and filters
- Conditional formatting
- Interactive dashboard design
- Data storytelling

## Project Structure

```text
retail-sales-analysis/
├── README.md
├── data/
│   └── cleaned_retail_sales.csv
├── powerbi/
│   └── retail_sales_dashboard.pbix
├── screenshots/
│   ├── page1_overview.png
│   ├── page2_product_analysis.png
│   └── page3_customer_analysis.png
└── python/
    └── data_cleaning.ipynb
```

## Conclusion

This project demonstrates an end-to-end retail sales analysis workflow, from data cleaning and preparation to data modeling, analysis, visualization, and interactive dashboard development.
