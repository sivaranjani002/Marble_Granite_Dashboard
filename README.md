📊 Key Dashboard Features
1. Management Overview

Provides management with a high-level view of overall business performance through interactive KPIs and visualizations.

KPIs:

Total Sales
Total Profit
Profit Margin %
Total Quantity Sold
Current Stock
Total Customers
Total Products

Visualizations:

Monthly Sales Trend
Category-wise Sales
Location-wise Sales
Payment Status
Top 5 Products by Sales

Business Purpose:
Helps management quickly understand overall sales performance, profitability, customer activity, and revenue-generating products.

2. Sales Analysis

Provides detailed analysis of customer and product sales performance.

Analysis includes:

Product-wise Sales and Profit
Customer-wise Sales
Top Customers
Monthly Quantity Sold

Business Purpose:
Identifies best-selling products, high-value customers, sales trends, and profitable products, helping management understand what products and customers are driving revenue.

3. Inventory Analysis

Monitors inventory levels and stock movement across products.

Analysis includes:

Current Stock by Product
Total Stock Value
Purchased vs Sold Quantity
Low-stock Products

Business Purpose:
Helps prevent stock shortages and identify products with low or excess inventory. Management can use this information to plan future purchases and maintain appropriate stock levels.

4. Purchase & Supplier Analysis

Provides visibility into purchasing activities and supplier contribution.

Analysis includes:

Total Purchase Amount
Supplier-wise Purchases
Product-wise Purchase Quantity
Monthly Purchase Trend

Business Purpose:
Helps management understand purchasing patterns, supplier contribution, product procurement volume, and monthly purchasing trends, supporting better inventory and supplier management.

📁 Data Model

The dashboard is built using multiple structured tables:

Sales Table

Contains transaction-level information such as:

Order/Invoice
Date
Customer
Product
Quantity
Selling Price
Sales Amount
Profit
Payment Status
Pending Amount
Products Table

Contains product master information:

Product
Category
Selling Price
Cost Price
Margin %
Customers Table

Contains:

Customer
Customer Type
Location
Purchases Table

Contains:

Purchase Date
Supplier
Product
Quantity Purchased
Purchase Price
Purchase Amount
Stock Table

Contains:

Opening Stock
Purchased Quantity
Sold Quantity
Closing Stock
Stock Value

📐 Key DAX Measures
Total Sales =
SUM(Sales[Sales_Amount])
Total Profit =
SUM(Sales[Profit])
Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)
Total Quantity Sold =
SUM(Sales[Quantity_sqft])
Total Stock Value =
SUM(Stock[Stock_Value])
Total Purchases =
SUM(Purchases[Purchase_Amount])

💼 Business Impact

The dashboard enables management to:

Monitor overall sales and profitability
Identify top-performing and slow-moving products
Analyze customer purchasing behavior
Track pending and completed payments
Monitor current inventory and stock value
Identify low-stock products
Compare purchased vs sold quantities
Evaluate supplier purchasing contribution
Analyze monthly sales and purchase trends
Make faster, data-driven business decisions
