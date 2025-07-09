# Adventure-Works-PI-Final-Dashboard

This data model represents a star schema commonly used in data warehousing and Power BI reporting. Here's a brief description:
Fact Table (Sales Data): Central table containing transactional data such as OrderDate, OrderQuantity, ProductKey, Revenue, and CustomerKey. It is connected to several dimension tables.

Dimensions:
Customer Lookup: Holds customer attributes like name, income, gender, and priority.
Product Lookup: Stores product details such as name, SKU, cost, and subcategory.
Calendar Lookup: Provides date-related attributes like day, month, and week for time-based analysis.
Territory Lookup: Includes geography-related data such as country and region.
Product Subcategories and Product Categories Lookup: Define product hierarchy for deeper insights.
Returns Data: Tracks returned products along with return date and quantity.

Other Tables:
Price Adjustment (%): Contains price adjustment percentage values.
Explicit Measure: Likely a measure table with pre-calculated KPIs like % of All Orders.

![Schema Diagram ](https://github.com/user-attachments/assets/b6e49e35-e515-4c4d-9c4e-c6bdf2fcba58)
