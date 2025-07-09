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

![1](https://github.com/user-attachments/assets/642be9e8-f7da-4013-95de-30928de15f7b)
![2](https://github.com/user-attachments/assets/a7937d20-ce6b-4ce2-9ce6-5a3dd2c55329)
![3](https://github.com/user-attachments/assets/c37f701f-0d31-4f5f-973d-640bbcc3d677)
![4](https://github.com/user-attachments/assets/90c3a21f-ef87-4904-bbdd-22184bd05549)
![5](https://github.com/user-attachments/assets/a2251cfb-dcf4-4e30-9996-a1cbbe929a5d)
![6](https://github.com/user-attachments/assets/3a3d00f3-c6ab-4877-8f96-ce1c9133a064)
![7](https://github.com/user-attachments/assets/c854be93-36d7-4b32-acd7-acb0ec8462d3)






