# Market Basket Analysis | Retail Transaction Analytics

### Analyzing Customer Purchasing Behaviour Through SQL, Python, Association Rule Mining & Power BI

## Project Overview

This capstone project explores retail transaction data to understand customer purchasing behaviour, evaluate sales performance and identify product associations.

Using the **Online Retail dataset containing approximately 541,909 transaction records**, the project combines SQL-based data cleaning, Python-based exploratory analysis, Apriori association rule mining and Power BI visualization to derive insights into retail sales and purchasing patterns.

## Business Problem

The online retail business generates substantial transaction data but needs better visibility into sales performance, customer purchasing patterns and relationships between products.

This project addresses the following business questions:

- Which products generate the highest and lowest sales?
- Which countries contribute the most and least revenue?
- Which products are purchased most frequently?
- How does revenue vary across months and years?
- Which products are commonly purchased together?
- How can product associations support cross-selling and product recommendations?

## Technology Stack

| Technology | Application |
|---|---|
| Microsoft Excel | Initial data understanding |
| SQL Server | Data cleaning and preprocessing |
| Python | Data analysis and EDA |
| Pandas, NumPy | Data manipulation and analysis |
| Matplotlib, Seaborn | Exploratory data visualization |
| Apriori, mlxtend | Frequent itemset and association rule mining |
| Power BI | Interactive dashboards and reporting |
| DAX | Dashboard calculations and measures |

## Project Workflow

### 1. Data Understanding
- Explored the Online Retail dataset and its transaction-level attributes.
- Examined invoice numbers, product descriptions, quantities, unit prices, invoice dates, customer IDs and countries.
- Identified relevant business questions for further analysis.

### 2. Data Cleaning & Preprocessing — SQL Server
- Removed records containing missing values.
- Standardized product descriptions using SQL `LTRIM()` and `RTRIM()` functions.
- Converted invoice numbers to string format.
- Excluded postage-related records.
- Separated invoice date and time into individual columns.
- Removed records containing negative quantities as specified in the SQL cleaning workflow.

### 3. Exploratory Data Analysis — Python
Performed descriptive and exploratory analysis to investigate:

- Transaction distribution across countries.
- Total revenue and geographical sales performance.
- Top and bottom five countries by revenue.
- Customer distribution across countries.
- Revenue trends across years and months.
- Product-level revenue and sales quantities.

Created a total amount measure using quantity multiplied by unit price to evaluate sales performance.

### 4. Market Basket Analysis — Apriori Algorithm
Applied association rule mining to identify products frequently purchased together.

Key implementation steps:
- Grouped products into transaction baskets using invoice numbers.
- Converted transaction baskets into a binary representation of product presence.
- Generated frequent itemsets using the Apriori algorithm.
- Generated and evaluated association rules using Support, Confidence and Lift.
- Filtered product associations based on rule strength and confidence.

### 5. Interactive Dashboard Development — Power BI

Developed three dashboard sections:

**Revenue Analysis**
- Revenue performance across countries.
- Product-level sales analysis.
- Revenue trends and geographical comparisons.

**Customer Analysis**
- Customer distribution across countries.
- Customer purchasing patterns.
- Geographical customer insights.

**Market Basket Analysis**
- Frequently purchased product combinations.
- Product association patterns.
- Association rule analysis using relevant measures and DAX calculations.

## Business Applications

The analysis provides a foundation for retail decision-making:

- **Cross-selling:** Identify complementary products for recommendation strategies.
- **Product Bundling:** Explore frequently purchased product combinations.
- **Sales Strategy:** Understand geographical and product-level revenue performance.
- **Inventory Planning:** Use purchasing patterns to inform product availability decisions.
- **Customer Insights:** Understand customer distribution and purchasing behaviour.

## Key Skills Demonstrated

SQL Data Cleaning | Python Data Analysis | Exploratory Data Analysis | Statistical Measures | Association Rule Mining | Apriori Algorithm | Data Visualization | Power BI | DAX | Retail Analytics

## Project Deliverables

- SQL Server data cleaning and preprocessing scripts.
- Python Jupyter Notebook for data analysis and association rule mining.
- Interactive Power BI report.
- Project presentation and documentation.

## Author

**Satyanarayan Mishra**

[GitHub Profile](https://github.com/Satyanarayan23)
