# Sales and Customer Analytics SQL Project

Welcome to my 3d SQL project!

This project consists of a comprehensive set of SQL queries aimed at analyzing sales performance, customer behavior, and product performance using data from a hypothetical retail company. The dataset includes information about customers, products, and sales transactions.

**You can find all the queries in "warehouse_sales_queries.sql" file.**

## Tables

The following main tables are used in the analysis:

- `customers`: Contains personal and demographic information about customers.
- `products`: Contains detailed information about the products sold.
- `sales`: Contains records of each sales transaction, including quantities and revenue.

---

## SQL Analysis Sections

### 1. **Changes Over Time Analysis**
This section shows monthly sales trends over time, tracking the total sales amount, the number of unique customers, and the quantity sold. Useful for identifying seasonality and growth patterns.

### 2. **Cumulative Analysis**
Calculates cumulative sales per year and moving average product prices. This helps visualize long-term trends and average pricing behavior.

### 3. **Performance Analysis**
Assesses product-level performance over the years. It compares each year’s sales with historical averages and previous years, identifying products with improving or declining performance.

### 4. **Part-to-Whole Analysis**
Breaks down total sales by product categories and calculates the percentage contribution of each category. Helps identify which product categories are driving most of the revenue.

### 5. **Data Segmentation**
Segments customers and products:
- Customers are grouped as VIP, Regular, or New based on their spending and loyalty (months since first purchase).
- Products are grouped into cost ranges for better understanding pricing structures and market positioning.

### 6. **Customers Report**
Creates a view `report_customers` that aggregates customer data: age, total orders, total sales, average order value, and monthly spending. It includes segmentation by age group and customer segment, useful for targeted marketing and retention strategies.

### 7. **Products Report**
Creates a view `report_products` summarizing product performance: total orders, sales, customer count, average selling price, and revenue trends. Products are categorized into High, Mid, and Low performers based on total revenue.

---

## How to Use

1. Execute the table creation scripts to create the schema and load the data.
2. Run the analysis queries section by section.
3. Use the created views `report_customers` and `report_products` to support dashboards or deeper BI tools.

---

## Conclusion

This SQL project provides a full analysis pipeline for retail data. It includes trend tracking, segmentation, product performance, and customer behavior insights — a solid foundation for decision-making in sales, marketing, and product development.

Thank you for your attention, please feel free to download this project!
