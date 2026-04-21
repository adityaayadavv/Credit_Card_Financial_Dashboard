💳 Credit Card Financial Dashboard (Power BI + SQL Server)
An end-to-end Business Intelligence project that analyzes credit card transactions and customer data using SQL Server as the backend and Power BI for interactive visualization.
This project demonstrates how real-world dashboards are built using live/refreshable databases, enabling dynamic insights as data updates.


📊 Project Overview
This dashboard provides insights into:
  -Financial performance (Revenue, Interest, Transactions)
  -Customer segmentation & behavior
  -Spending patterns and transaction modes
  -Demographics and income distribution

🔗 Key Highlight:
Power BI is connected to a SQL Server database, so any updates in the database are automatically reflected in the dashboard (on refresh).


🏗️ Architecture
SQL Server Database  →  Data Modeling (Relationships)  →  Power BI Dashboard
        ↑
   Data Updates
        ↓
   Dashboard Refresh

-Data is stored and managed in SQL Server
-Queries and transformations handled via SQL + Power BI
-Dashboard updates dynamically with new data


🧩 Dashboards
🔹 Credit Card Transaction Report
Focuses on financial metrics and transaction analysis.
Key KPIs:
  💰 Total Revenue: 55.4M
  💵 Total Interest: 7.9M
  💳 Transaction Amount: 45M
  🔢 Transaction Count: 657K
Insights:
  -Revenue by card category (Blue, Silver, Gold, Platinum)
  -Quarterly revenue trends
  -Revenue by expenditure type
  -Revenue by education & job
  -Transaction mode analysis (Swipe, Chip, Online)
  
🔹 Credit Card Customer Report
Focuses on customer segmentation and demographics.
Key KPIs:
  💰 Total Revenue: 55.4M
  💵 Total Interest: 7.9M
  🧾 Total Income: 577M
  📈 Customer Satisfaction Score: 3.19
Insights:
  -Revenue by gender
  -Age group analysis
  -Job-wise revenue contribution
  -Top-performing states
  -Salary group segmentation
  -Dependents & marital status analysis
  -Education level distribution


🔄 Data Flow
  1.Data is stored in SQL Server
  2.Power BI connects using SQL Server connection
  3.Data is imported or queried
  4.Dashboard updates on refresh


🚀 Features
  🔄 Real-time / refresh-based data updates
  🎯 Interactive slicers (Quarter, Gender, Card Type, Income)
  📊 Dynamic KPIs and visuals
  🧠 Business-focused insights

📌 Key Business Insights
  -Blue card category contributes the highest revenue
  -Bills and entertainment dominate spending
  -High-income customers drive maximum revenue
  -Self-employed and business professionals are major contributors
  -Swipe transactions are the most used mode
