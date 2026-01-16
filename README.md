# Shopping Trend_Analysis
This project is an end-to-end Data Analytics project is built with the help of Python, SQL, and Power BI to know the  customers shopping behavior and identify key revenue drivers.
 
 📌 Overview

This project evaluate customer shopping behaviour to drive strategics meaningful business insights using Python, SQL, and Power BI fro visualization.
The workflow covers:
Loading and cleaning data in Python.
Performing Exploratory Data Analysis (EDA).
Running business-focused SQL queries in MySQL.
Building an interactive Power BI dashboard.
Creating a professional report and presentation.



📊 Dataset

File: shopping_trends.csv.
Summary table created from inested data and used for analysis.


🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn).
- SQL (MySQL).
- Power BI (Data Modeling, DAX, Dashboarding).
- Gamma → PPT & Report Generation.
- GitHub.



🔁 Project Steps

1. Data Loading (Python).
- Load CSV using Pandas.
import pandas as pd
df = pd.read_csv("shopping_trends.csv").

2. Exploratory Data Analysis (EDA).
- Check shape, columns, data types.
- Identify missing values.
- Analyze distributions and outliers.
- Understand customer behavior patterns.
  
3. Data Cleaning
- Handle missing values.
- Standardize text fields (Yes/No, Male/Female).
- Convert data types.
- Remove duplicates.
- Rename columns for clarity.
  
4. Load Cleaned Data into MySQL
- Create database and table.
- Insert cleaned data.
- Validate row count and schema.
  
5. SQL Analysis
Key business questions answered:
- Revenue by gender.
- Impact of discounts on revenue.
- Subscription vs non-subscription spending.
- Customer segmentation (New / Returning / Loyal).
- Top products per category.
- Age group revenue contribution.
  
6. Power BI Dashboard
Built a professional Shopping Trend Dashboard including:
KPI Cards:
- Total Revenue
- Number of Customers
- Average Order Value (AOV)
- Average Review Rating
  
Charts:
- Revenue by Category.
- Revenue by Gender.
- Subscription Status Distribution.
- Revenue by Age Group.
- Shipping Type vs Spend.
  
Slicers:
- Gender
- Subscription Status


📊 Results & Key Insights.

- Clothing category generates the highest revenue.
- Subscribed customers have higher lifetime value.
- Express shipping users spend more on average.
- Discounts increase purchase frequency but can reduce AOV.
- Young adults contribute the most to total revenue.
- Loyal customers are the strongest revenue contributors.


📈 Dashboard Output

The dashboard presents:
- Business performance at a glance
- Customer behavior insights
- Product and category performance
- Impact of subscriptions and discounts
  
<img width="776" height="440" alt="image" src="https://github.com/user-attachments/assets/5c8b79de-db70-47c2-974d-15390d2a6c87" />


▶️ How to Run the Project

1.Clone the repository.
   https://github.com/deep1652000/shopping_trend_analytics_dashboard/tree/main

2.Run Python notebooks:
pip install pandas numpy matplotlib seaborn
Open Jupyter Notebook and run EDA & cleaning files.
3.Load cleaned data into MySQL.
- Create database.
- Import CSV using MySQL Workbench or Python.
4.Run SQL queries from /sql_queries.sql.
5.Open Power BI:
- Load cleaned CSV or connect to MySQL.
- Refresh data.
- View dashboard.
