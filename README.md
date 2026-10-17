## Project Overview
The goal of this project is to turn raw e-commerce order data into an interactive dashboard that helps users monitor business performance and identify trends by product category, state, payment mode, and order status.
### Dashboard Preview

## Tools & Technologies
- Microsoft Excel:— source data and initial review
- Python / Pandas:— data cleaning, transformation, and derived columns
- SQL Server:— storing and querying the processed dataset
- Power BI:— interactive dashboard and visual reporting
- GitHub:— project documentation and portfolio presentation
## Data Pipeline
##### Excel source data
##### Python (Pandas): cleaning and transformation
##### SQL Server: data storage / querying
##### Power BI: data model, measures, visuals, dashboard
## Dataset
The cleaned CSV supplied with this project contains **513 rows and 21 columns**. Fields include:
- Order details: Order_ID,Order_Date,Order_Status.
- Customer and location: Customer_Name,Email,Phone,City,State.
- Product details: Product,Category,Qty,Unit_Price,Discount.
- Payment and delivery: Payment_Mode,Delivery_Date.
- Financial metrics: Sales,Net_Amount,Profit.
- Date attributes: Month,Year,Day.
## Dashboard KPIs
- Count of Order_ID 
- Total Sales 
- Net Revenue 
- Total Profit 
- Average Order Value
- Profit Margin
## Dashboard Visuals
- Sales by State:— geographic distribution of sales
- Sales by Category:— compares Electronics, Fashion, Furniture, and Home
- Payment Mode by Orders:— compares COD, Wallet, Netbanking, UPI, and Card
- Monthly Sales Trends:— tracks sales over time
- Order Status:— compares Delivered, Returned, Cancelled, and Pending orders.
- Interactive filters:— category buttons and an order-date range slicer
## Business Questions
- Which product category generates the highest sales?
- Which states contribute most to sales?
- Which payment methods are used most often?
- How do sales change over time?
- What share of orders are delivered, returned, cancelled, or pending?
- How do sales, net revenue, and profit change when a category or date range is selected?
## Key Insights From the Current Dashboard
- Electronics is the leading category by sales in the displayed view.
- COD and Wallet are among the highest order-count payment methods in the displayed chart.
- 20% profit margin.
- Order statuses are distributed across Delivered, Returned, Cancelled, and Pending, so fulfilment and returns are useful areas for further investigation.
- The state map supports geographic exploration; use its tooltips to inspect the underlying values.



