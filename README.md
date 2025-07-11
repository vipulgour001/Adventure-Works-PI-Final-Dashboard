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


**📂 Dataset Introduction – Adventure Works**

The Adventure Works dataset is a widely used sample business dataset provided by Microsoft, designed to simulate a real-world retail and manufacturing company specialising in outdoor gear and cycling products. It contains rich and diverse data across multiple domains, making it ideal for analytics, dashboard development, and business intelligence use cases.

**🧩 Key Features:**

Business Domain: Retail / E-commerce (Adventure sports and cycling products)

Core Data Areas:

Sales data (revenue, profit, order volume)
Product details (categories, subcategories, pricing, return rates)
Customer information (demographics, income level, occupation, purchase history)
Time series (monthly performance over multiple years)
Geographic segmentation (e.g., North America, Europe, Pacific regions)

🎯 **Use Case Applications:**

Performance tracking (revenue, profit, return rate)
Sales trend analysis and forecasting
Customer segmentation and behaviour analysis
Product performance comparison
Key influencer and anomaly detection



**🔍 Overview:**

The Power BI dashboard provides a comprehensive view of sales performance, customer demographics, and product metrics for an adventure retail business. It covers revenue, profits, order trends, product returns, and customer behaviour across time and categories.

**📊 Key Metrics:**

Total Revenue: $24.9M,
Total Profit: $10.5M,
Orders: 25.2K,
Return Rate: 2.2%,
Monthly Revenue (Latest): $1.83M (↑ 3.31% from previous month),
Revenue per Customer: $2.4K $
Unique Customers: 2,630

**📈 Performance Trends:**

Monthly revenue is showing a positive trend.
Adjusted profit rose by 140.91% from June 2021 to June 2022.
Revenue dipped unexpectedly on July 1, 2021 to $1,059, below expected levels.

**📦 Top-Selling Products (by Orders)**

Water Bottle - 30 oz. – 3,983 orders,
Patch Kit/8 Patches – 2,952 orders,
Mountain Tire Tube – 2,846 orders $
Sport-100 Helmet (Red/Blue/Black) – High revenue but relatively higher return rates (up to 3.33%)

**🛑 Most Ordered Product Type: Tires and Tubes**

**🧑‍🤝‍🧑 Customer Demographics:**

Most Orders by Income: 43.73% of customers fall within mid-income brackets.
Top Occupations: Management, Skilled Manual, and Clerical roles.
Key Influencers: Marital status, parental status, education, and income significantly influence home ownership among customers.

**🎯 Performance vs Targets:**

Revenue, profits, and orders show slight underperformance relative to set targets in recent months.

**🔎 Insights:**

The analysis reveals that higher product costs are strongly correlated with increased product prices, highlighting a direct cost-to-price relationship that can guide pricing strategies. Additionally, customer segmentation insights show that certain demographic traits—such as being married, having children, earning an income between $30K and $120K, and holding higher education degrees—significantly increase the likelihood of homeownership, which can be valuable for targeted marketing campaigns. Moreover, product category trends indicate that accessories and helmets are among the top contributors to overall revenue, underscoring their popularity; however, they also exhibit higher return rates, suggesting potential quality concerns that should be addressed to maintain customer satisfaction and brand reputation


✅ Overall Strategic Recommendation

To drive business growth, a focused product strategy is essential—bestselling items with low return rates should be actively promoted through marketing and sales channels, while products with high return rates, such as certain helmet models, should be thoroughly reviewed for potential quality issues. Strengthening customer loyalty is another key priority; high-spending and repeat customers can be incentivized with personalised offers, loyalty programs, and exclusive rewards to encourage retention and increase lifetime value. In terms of market expansion, regions like Australia, which show promising performance, should be leveraged further, while efforts should also be made to analyze and improve underperforming geographies through localized strategies. On the pricing front, implementing the cost-to-price influencer model can help strike the right balance between profitability and market competitiveness by aligning pricing with production costs and customer willingness to pay. Lastly, the use of Power BI dashboards should be continued and enhanced to support real-time data monitoring, enable early anomaly detection, and drive data-driven decision-making across departments.
