**Marble & Granite Business Dashboard**

This project is a Power BI dashboard designed for a marble and granite trading company. It provides a comprehensive business overview across sales, inventory, purchases, and supplier performance, enabling management to make data‑driven decisions.

**Key Features**
Management Overview  
High‑level KPIs: Total Sales, Profit, Margin %, Quantity Sold, Current Stock, Customers, Products.
Visuals: Monthly Sales Trend, Payment Status, Location‑wise Sales, Category‑wise Sales, Top 5 Products.

**Sales Analysis**  
Product‑wise Sales & Profit comparison.
Customer‑wise Sales table.
Top Customers ranking.
Monthly Quantity trend line chart.

**Inventory**  
Current Stock by product.
Total Stock Value card.
Purchased vs Sold comparison chart.
Low‑stock Products table (threshold filter).

Purchase & Supplier  
Total Purchases card.
Supplier‑wise Purchases bar chart.
Product‑wise Purchases matrix.
Monthly Purchase Trend line chart.

**Data Sources**
Sales table → Orders, customers, payment status.

Stock table → Opening, purchased, sold, closing stock.

Purchases table → Supplier transactions.

Products table → Selling price, cost price, margin %.

Customers table → Customer type and location.

**KPIs Defined**
Total Sales = SUM(Sales[Sales_Amount])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Total Quantity Sold = SUM(Sales[Quantity_sqft])

Total Stock Value = SUM(Stock[Stock_Value])

Total Purchases = SUM(Purchases[Purchase_Amount])

**Business Benefits**
Identify top products and customers driving revenue.

Track payment status (Paid vs Pending).

Monitor low‑stock items to avoid shortages.

Evaluate supplier contribution and monthly purchase trends.

Provide management with clear KPIs for decision‑making.
