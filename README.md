# FNP-Sales-Performance-Analysis
I developed a comprehensive end-to-end sales performance and analytics project using Power Query, Power Pivot, and sAdvanced Microsoft Excel for the Ferns N Petals (FNP) dataset.

## Project  overview
This project is an end-to-end Sales Performance and E-commerce Analytics dashboard built using Advanced Microsoft Excel. It analyzes 1,000 orders from the Ferns N Petals (FNP) dataset to uncover key insights related to revenue generation, seasonal festival demand (Raksha Bandhan, Valentine's Day), product popularity, customer spending patterns, and delivery logistics.

##Dataset used
-<a href="https://github.com/Deepak-xh/FNP-Sales-Performance-Analysis/blob/main/customers.csv">customersDataset</a>
-<a href="https://github.com/Deepak-xh/FNP-Sales-Performance-Analysis/blob/main/orders.csv">ordersDataset</a>
-<a href="https://github.com/Deepak-xh/FNP-Sales-Performance-Analysis/blob/main/products.csv">productsDataset</a>

## Technical Workflow & Process:
1. ETL & Data Preprocessing (Power Query):
   - Extracted and transformed raw data sources.
   - Performed data cleaning, typecasting, and formatting date-time attributes.
2. Data Modeling & Architecture (Power Pivot):
   - Built a relational Data Model (Star Schema).
   - Configured one-to-many primary-to-foreign key relationships between the orders (Fact Table), customers, and            products (Dimension Tables).
3. Feature Engineering & Calculations:
   - Developed calculated columns for line-item revenue (Price × Quantity), order-to-delivery lead time (Delivery_Date       - Order_Date), and hour/month extraction.
4. Multi-Table Reporting & Data Visualization:
   - Created multiple dynamic Pivot Tables and Pivot Charts to track monthly performance, top products, category shares, and city-wise order distribution.
   - Built a single-page interactive **Executive Dashboard** empowered by synchronized Slicers, Timeline filters, and dedicated summary sheets.
  


## Business Problem Addressed
Analyzed sales trends, delivery turnaround times, customer spending patterns, and festive seasonality to uncover operational and revenue growth opportunities.

## Key Performance Indicators (KPIs)
- Total Revenue: ₹35,20,984
- Total Orders: 1,000
- Average Order Value (AOV): ₹3,521
- Average Delivery Lead Time:5.53 Days
- Active Customers: 100

## Key Business Insights
1. Seasonal Demand : August (Raksha Bandhan - ₹7.37L) and February (Valentine's - ₹7.05L) are primary revenue drivers.
2. Category Dominance: Colors (28.6%), Soft Toys (21.0%), and Sweets (20.8%) account for over 70% of total revenue.
3. Hourly Ordering Behavior: Peak ordering occurs at 6:00 PM in February and between 8:00 PM – 10:00 PM in August.
4. Logistics Optimization: Delivery takes an average of 5.53 days, presenting an opportunity for same-day express delivery in top metro cities.

##  Insights and kpi
-<a href="https://github.com/Deepak-xh/FNP-Sales-Performance-Analysis/blob/main/fnp%20kpi%20%20and%20insight.pdf">inights_pdf</a>

## Dashboard
-<a href="https://github.com/Deepak-xh/FNP-Sales-Performance-Analysis/blob/main/fnp_project_dashboard.PNG">dahboard_ss</a>


## Conclusion & Key Takeaways
 Project Impact: Successfully converted raw e-commerce gifting data into an interactive and professional analytics dashboard using Advanced Excel.
Core Revenue Drivers: Festive seasons (**Raksha Bandhan** in August and **Valentine's Week** in February) are the biggest revenue boosters, while top categories like **Colors, Soft Toys, and Sweets** generate over 70% of total sales.
Operational Insight: Average delivery time of **5.53 days** highlights an opportunity to introduce express or same-day delivery for perishable items like cakes and sweets.
Future Scope: Can be scaled further by integrating automated inventory forecasting, regional city-tier logistics tracking, and customer retention campaigns.




