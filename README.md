# Zepto SQL Analysis Project

A comprehensive SQL-based data exploration, cleaning, and analysis project on Zepto (quick commerce platform) product data.

## 📋 Project Overview

This project demonstrates end-to-end SQL skills by working with a real-world e-commerce dataset from Zepto. It includes table creation, data exploration, data cleaning, and multiple analytical queries to derive business insights.

### Objectives
- Perform exploratory data analysis (EDA) on product catalog
- Clean and transform raw data
- Answer key business questions through SQL queries
- Analyze pricing, discounts, inventory, and product categories

## 🗂️ Dataset

The dataset contains product information from Zepto with the following columns:

- `sku_id`: Unique product identifier (Primary Key)
- `category`: Product category
- `name`: Product name
- `mrp`: Maximum Retail Price (in paise initially)
- `discountPercent`: Discount percentage
- `availableQuantity`: Stock available
- `discountedSellingPrice`: Selling price after discount
- `weightInGms`: Product weight in grams
- `outOfStock`: Boolean flag for stock status
- `quantity`: Additional quantity field

## 🛠️ Technologies Used

- **PostgreSQL** (compatible with most SQL databases)
- **SQL** (DDL, DML, Aggregations, Window functions, CASE statements)
- **Git** & GitHub

## 📁 Project Structure

zepto-sql-analysis/
├── zepto_SQL_project.sql     # Main SQL script
├── README.md                 # Project documentation
└── (optional) data/          # Raw data files (if available)
text


📊 Analysis Performed
1. Data Exploration

Total record count
Sample data viewing
Null value detection
Unique categories
Stock status distribution
Duplicate product names

2. Data Cleaning

Removed products with zero MRP
Converted price values from paise to rupees
Handled data quality issues

3. Key Business Queries
Q1. Top 10 best-value products by discount percentage
Q2. High MRP products that are currently out of stock
Q3. Estimated revenue potential per category
Q4. Premium products (MRP > ₹500) with low discount (<10%)
Q5. Top 5 categories with the highest average discount
Q6. Price per gram analysis for products ≥100g
Q7. Product weight categorization (Low/Medium/Bulk)
Q8. Total inventory weight per category
📈 Sample Insights

Identified categories with the highest revenue potential
Found the best discount offers and value-for-money products
Analyzed inventory distribution and stock health
Calculated price efficiency (₹ per gram)

🔍 Key SQL Techniques Used

GROUP BY and aggregate functions (SUM, AVG, COUNT)
CASE statements for categorization
Subqueries and filtering
ROUND() for clean output
ORDER BY with multiple columns

🎯 Future Enhancements

Add more advanced analytics (moving averages, year-over-year comparison)
Create views and stored procedures
Build data visualizations (Power BI / Tableau)
Add product recommendation logic
Performance optimization with indexes

🤝 Contributing
Contributions are welcome! Feel free to:

Improve existing queries
Add new analytical questions
Enhance documentation
Fix bugs or suggest optimizations

📄 License
This project is open source and available under the MIT License.

Made with ❤️ for SQL enthusiasts and data analysts
Feel free to star the repository if you found it helpful!

