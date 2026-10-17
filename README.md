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
Excel source data
 ↓
Python (Pandas): cleaning and transformation
      ↓
SQL Server: data storage / querying
      ↓
Power BI: data model, measures, visuals, dashboard
## Dataset
The cleaned CSV supplied with this project contains **513 rows and 21 columns**. Fields include:
- Order details: `Order_ID`, `Order_Date`, `Order_Status`
- Customer and location: `Customer_Name`, `Email`, `Phone`, `City`, `State`
- Product details: `Product`, `Category`, `Qty`, `Unit_Price`, `Discount`
- Payment and delivery: `Payment_Mode`, `Delivery_Date`
- Financial metrics: `Sales`, `Net_Amount`, `Profit`
- Date attributes: `Month`, `Year`, `Day`
The dataset includes customer contact fields. Before publishing data publicly, confirm that you have permission to share it and remove or anonymize personal information such as names, email addresses, and phone numbers. Prefer uploading an anonymized dataset or a small synthetic sample.



