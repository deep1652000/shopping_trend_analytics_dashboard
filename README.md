# Shopping Trend Analysis
This project is an end-to-end Data Analytics project is built with the help of Python, SQL, and Power BI to analyze customer shopping behavior and key revenue metrics.

 
 ## 📌 Overview

This project evaluate customer shopping data, performs exploratory analysis, answers business questions via SQL, and presents some insights with an interactive Power BI dashboard
The workflow covers:
- Loading and cleaning data in Python.
- Performing Exploratory Data Analysis (EDA).
- Running business-focused SQL queries in MySQL.
- Building an interactive Power BI dashboard.
- Creating a professional report and presentation.



## 📊 Dataset

- <a href="https://github.com/deep1652000/shopping_trend_analytics_dashboard/blob/main/customer_shopping_behavior%20(1).csv">Dataset</a>
- File: shopping_trends.csv.


## 🛠️ Tools & Technologies

- Python (Pandas, NumPy,EDA).
- SQL (MySQL).
- Power BI (Data Modeling ,Dashboard, DAX).
- Gamma → PPT.
- GitHub.



## 🔁 Project Steps

1. Data Loading (Python).
- Load CSV using Pandas.
- import pandas as pd.
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
- Category
- Shipping Types.


## 💡 Results & Key Insights.

- Clothing category generates the highest revenue.
- Subscribed customers have higher lifetime value.
- Express shipping users spend more on average.
- Discounts increase purchase frequency but can reduce AOV.
- Young adults contribute the most to total revenue.
- Female customers slightly outperform in total revenue.
- Loyal customers are the strongest revenue contributors.


## 📈 Dashboard Output

The dashboard presents:
- Business performance at a glance
- Customer behavior insights
- Product and category performance
- Impact of subscriptions and discounts
  
<img width="774" height="437" alt="Dashboard_Image png 2" src="https://github.com/user-attachments/assets/9ff9f4ec-e531-40c1-b4ef-3a0b314bd4db" />



## ▶️ How to Run the Project

1. Clone the repository.
   - https://github.com/deep1652000/shopping_trend_analytics_dashboard/tree/main

2. Run Python notebooks:
   - pip install pandas numpy matplotlib seaborn.
- Open Jupyter Notebook and run EDA & cleaning files.

3. Load cleaned data into MySQL.
- Create database.
- Import CSV using MySQL Workbench or Python.
 
4. Run SQL queries from /sql_queries.sql.

5. Open Power BI:
- Load cleaned CSV or connect to MySQL.
- Refresh data.
- View dashboard.
