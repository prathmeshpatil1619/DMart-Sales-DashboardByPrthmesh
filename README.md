📊 DMart-Sales-Dashboard By Prathmesh

Interactive Sales Dashboard for DMart built in Power BI using Power Query (ETL) for data cleaning and transformation.
The dashboard provides insights into orders, sales trends, customer distribution, payments, and subscriptions.

📌 Project Overview

This project explores DMart sales performance using Power BI.
The dashboard provides interactive insights into:

Total Orders, Cancel Orders, Customers, and Shipping Cost

Sales Trends (Monthly/Yearly)

Payment Method Analysis (Debit, Credit, UPI, Netbanking, COD)

Order Status Distribution (Delivered, Shipped, Cancelled, Returned)

Sales by Subscription (Freepass, Premium, Premium Plus)

Customer Demographics by Gender & Location

Average Customer Ratings

⚙️ ETL & Data Cleaning (Power Query Steps)

The raw data went through the following data cleaning & transformation steps:

1. Data Extraction

Imported multiple CSV/Excel files into Power BI via Power Query.

Combined datasets using Append Queries.

2. Data Cleaning

Removed duplicate entries (Customer IDs, Order IDs).

Handled missing values:

Filled blanks with “Unknown” for categorical fields.

Replaced null numeric values with 0.

Standardized column names (e.g., Cust_ID → CustomerID).

Corrected spelling errors in categories and states.

3. Data Transformation

Split columns (e.g., Full Name → First Name + Last Name).

Changed data types (Date → Date format, Sales → Currency).

Created conditional columns for Paid vs Pending Payments.

Added calculated fields:

Total Sales = Quantity * Unit Price

Profit = Sales - Cost

4. Data Loading

Loaded cleaned data into the Power BI model.

Built interactive visuals with measures and relationships.

📈 Dashboard Features

Filters (Slicers): State, Category, Subscription

KPIs: Total Sales, MTD Sales, YTD Sales, OTD Sales

Visuals Used:

📉 Line Chart → Sales Trend

📊 Stacked Column/Bar Chart → Payment Insights

🥧 Pie Chart → Order Status Distribution

🗺 Map Visual → Customer Distribution by Location

🎯 Gauge → Average Rating

📊 Stacked Bar → Subscription-wise Sales

🛠 Tools & Technologies

Power BI Desktop (Dashboard & Visualization)

Power Query (M Language) (ETL, Data Cleaning & Transformation)

DAX (Data Analysis Expressions) (Calculated Columns & Measures)

Data Sources: Synthetic DMart dataset (CSV/Excel)

📸 Preview
<img width="1785" height="745" alt="DMart Dashboard Preview" src="https://github.com/user-attachments/assets/280df2ff-45b7-422d-9574-85471bcfc7fa" />
📜 License

MIT License – Freely usable with attribution.
