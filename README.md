# customer_behavior_analysis
data analytics project showcasing customer behavior analysis using pythoa, sql and power Bi

**1.Overview**
This project focuses on analyzing customer purchase behavior using a real-world retail dataset. It demonstrates an end-to-end data analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL querying, and dashboard visualization.
The objective is to uncover insights related to customer demographics, purchasing patterns, and business performance to support data-driven decision-making.

**2.Dataset**
File: customer data analysis.csv
The dataset contains customer-level transactional data with attributes such as:
Age, Gender
Item Purchased & Category
Purchase Amount (USD)
Location & Season
Payment Method
Frequency of Purchases
Subscription Status, Discounts, Promo Codes
This dataset enables analysis of customer behavior, sales trends, and marketing effectiveness.

**3.Tools & Technologies**
Python (Pandas, Matplotlib, Seaborn) → Data cleaning & EDA
SQL (PostgreSQL / MySQL / SQL Server) → Data querying & analysis
Power BI → Interactive dashboard creation
Gamma → Presentation (PPT) creation
Jupyter Notebook → Development environment

**4.Project Workflow**
**4.1 Data Loading**
Imported dataset using Pandas
Explored structure, columns, and data types

**4.2 Exploratory Data Analysis (EDA)**
Analyzed customer demographics (age, gender)
Examined purchasing patterns across categories and seasons
Identified trends in spending and frequency
Visualized insights using charts

**4.3 Data Cleaning**
Checked and handled missing values
Standardized column formats
Removed inconsistencies
Ensured data readiness for analysis

**4.4 SQL Analysis**
Loaded cleaned data into relational databases
Performed:
Aggregations (total sales, average spend)
Grouping (category, gender, location)
Filtering (high-value customers, frequent buyers)
Extracted business insights using SQL queries

**4.5 Dashboard Development (Power BI)**
Built interactive dashboards showing:
Total Sales & KPIs
Category-wise performance
Customer segmentation
Purchase trends over time
Added slicers for dynamic filtering

**4.6 Reporting & Presentation**
Created a structured analytical report
Developed a presentation using Gamma
Highlighted insights, trends, and recommendations

5.**Dashboard**
The Power BI dashboard includes:
📌 Total Revenue & Key Metrics
📌 Sales by Category & Season
📌 Customer Demographics Analysis
📌 Purchase Frequency Insights
📌 Payment Method Distribution

6.**Key Insights**
-Certain product categories contribute the highest revenue
-Seasonal trends significantly impact purchasing behavior
-Customers using subscriptions or promo codes show different buying patterns
-Frequent buyers generate a large portion of total sales
-Payment methods vary across customer segments


7.**How to Run**
**step1 Clone the repository**
git clone <your-repo-link>
**step2 Install dependencies**
pip install pandas matplotlib seaborn
**step3 Run the notebook**
jupyter notebook customer_data_analysis_project.ipynb

8. **.SQL Setup**
Import dataset into PostgreSQL / MySQL / SQL Server
Run queries from /sql folder

9.**Open Power BI Dashboard**
Open .pbix file
Refresh data

10.**Project Structure**

1. data/customer data analysis.csv
2. notebooks/customer_data_analysis_project.ipynb
3. sql/ queries.sql
4. dashboard/ customer_data_analysis.pbix
5. presentation/gamma_presentation.ppt
6. README.md

11.**Conclusion**

This project demonstrates the complete data analytics lifecycle — from raw data to actionable insights. It highlights skills in data cleaning, analysis, SQL querying, and dashboard creation, making it a strong portfolio project for data analyst roles.
