# KPI Definitions

This document defines the 3-5 core Key Performance Indicators (KPIs) used in
the Sales Analytics Dashboard, including their formulas and business rationale.

## 1. Total Revenue
- **Formula:** SUM(Total_Sales)
- **Business Rationale:** Total Revenue is the primary measure of overall
  business performance. It shows how much income the business has generated
  across all orders and is the foundation for all other financial KPIs.

## 2. Total Orders
- **Formula:** COUNT(Order_Date)
- **Business Rationale:** Total Orders tracks the volume of demand. It helps
  the business understand how many transactions are happening, independent
  of order size, and is useful for operational planning (staffing, inventory,
  logistics).

## 3. Average Order Value (AOV)
- **Formula:** Total Revenue / Total Orders
- **Business Rationale:** AOV indicates customer spending behavior per
  transaction. A rising AOV suggests successful upselling/cross-selling,
  while a falling AOV may signal discount-driven purchases or smaller basket
  sizes. It directly informs pricing and promotion strategy.

## 4. Revenue by Category
- **Formula:** SUM(Total_Sales) grouped by Category
- **Business Rationale:** Identifies which product categories drive the most
  revenue, helping prioritize inventory investment and marketing spend
  toward high-performing categories like Electronics.

## 5. Revenue by City
- **Formula:** SUM(Total_Sales) grouped by City
- **Business Rationale:** Reveals geographic performance differences,
  helping the business decide where to expand operations, run regional
  promotions, or improve logistics/delivery coverage.