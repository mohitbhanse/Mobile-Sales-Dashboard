# Mobile-Sales-Dashboard
📊 Mobile Sales Dashboard (Power BI Project)
🧭 Overview

This project showcases a Mobile Sales Dashboard built in Microsoft Power BI to analyze and visualize sales performance across various dimensions — including brand, payment method, city, and time period.
The dashboard provides actionable insights for decision-making, tracking KPIs like Total Sales, Total Transactions, Total Quantity, and Average Price with an interactive and visually appealing interface.

🗂️ Dataset

Dataset Name: Mobile_sales_Data

Description: Contains transactional and sales data for multiple mobile brands across different cities.

Key Columns:

Date

Brand

Mobile Model

Payment Method

City

Total_Sales

Total_Transactions

Quantity

Average_Price

🛠️ Tools & Technologies

Power BI – Data visualization and report creation

Excel / SQL – Data preprocessing and cleaning

Custom Calendar Table – For time intelligence functions (MTD, YTD, and comparisons)

DAX (Data Analysis Expressions) – For calculated measures and KPIs

🔍 Project Steps

Data Loading: Imported dataset into Power BI from Excel.

Data Cleaning: Verified data consistency, formatted columns, and handled missing values.

Data Modeling: Created relationships between Mobile_sales_Data and Custom_Calendar tables.

DAX Calculations: Built measures such as:

Total Sales = SUM(Mobile_sales_Data[Total_Sales])

MTD Sales, Same Period Last Year, etc.

Visualization: Designed 3 interactive report pages:

Mobile Sales Dashboard

MTD Report

Same Period Last Year Report

📈 Dashboard Pages
1️⃣ Mobile Sales Dashboard

Displays KPIs: Total Sales, Total Transactions, Total Quantity, Average Price

Visuals:

Total Sales by City (Map)

Quantity Trend by Month

Transactions by Payment Method

Sales by Mobile Model

Customer Rating Analysis

Includes slicers for Month, Brand, Mobile Model, and Payment Method

🖼️

2️⃣ MTD Report (Month-to-Date)

Tracks MTD performance trends across multiple years.

Helps in comparing monthly growth patterns and seasonal trends.

🖼️

3️⃣ Same Period Last Year

Compares Total Sales and Same Period Last Year Sales by Year, Quarter, and Month.

Enables year-over-year growth analysis.

🖼️

📊 Key Insights

📌 Highest sales achieved by Apple and OnePlus brands.

💳 Most preferred payment method: UPI and Credit Card.

🌆 Top-performing cities: Mumbai, Delhi, and Bangalore.

📅 Steady MTD growth observed till mid-2024 with seasonal sales peaks.


💻 How to Run

Clone this repository:

git clone https://github.com/Mohit_bhanse/Mobile-Sales-Dashboard.git


Open the .pbix file in Power BI Desktop.

Refresh data connections if required.

Explore dashboard pages interactively.



🏁 Conclusion

This dashboard offers a complete view of mobile sales performance, enabling better decision-making through interactive visuals and comparative time-based insights. It’s a great example of data storytelling using Power BI.
