📊 Customer Shopping Behavior Analysis – End-to-End Data Analytics Project
🔍 Overview

This project demonstrates a complete end-to-end data analytics pipeline using a customer shopping behavior dataset. The goal is to analyze customer purchasing patterns, clean and transform raw data, perform SQL-based analysis, and present actionable insights through an interactive dashboard and reports.

The project simulates a real-world business scenario, showcasing skills in data cleaning, feature engineering, SQL analysis, and data visualization.

📁 Dataset
Dataset: Customer Shopping Behavior Dataset
Records: 3,900 rows, 18 columns

Key Features:
Customer demographics (age, gender, location)
Purchase details (item, category, amount)
Behavioral metrics (previous purchases, frequency)
Transaction attributes (payment method, shipping type, discounts)


🛠️ Tools & Technologies
Python (Pandas) – Data cleaning & preprocessing
SQL (PostgreSQL, MySQL, SQL Server) – Data storage & querying
Power BI – Dashboard creation
Gamma – Presentation (PPT)
Jupyter Notebook – Development environment

⚙️ Project Workflow

1. Data Loading
Loaded CSV dataset using Pandas
Performed initial inspection using .head(), .info(), .describe()

2. Data Cleaning
Identified missing values in review_rating
Imputed missing values using median grouped by category
Standardized column names to snake_case
Removed redundant column (promo_code_used)

3. Feature Engineering
Created age_group using quartile-based segmentation
Young Adult, Adult, Middle-aged, Senior
Converted purchase frequency into numeric format (purchase_frequency_days)
Mapped categorical frequency values (Weekly, Monthly, etc.) into days
Ensured data consistency between discount_applied and promo usage

4. Exploratory Data Analysis (EDA)
Analyzed:
Distribution of age and purchase amounts
Category-wise purchase trends
Customer behavior across seasons and locations
Identified key patterns and anomalies

5. SQL Integration
Connected Python with multiple databases:
PostgreSQL (psycopg2 + SQLAlchemy)
MySQL (PyMySQL + SQLAlchemy)
SQL Server (pyodbc + SQLAlchemy)
Exported cleaned dataset into SQL tables
Enabled structured querying for business insights

6. SQL Analysis (Examples)
Customer segmentation based on purchase history
Aggregations:
Total revenue
Average purchase value
Behavioral insights:
Purchase frequency trends
Category-wise performance
Filtering and joins for deeper analysis

7. Dashboard Creation (Power BI)
Built an interactive dashboard including:
KPIs: Total Sales, Avg Purchase, Customer Count
Category-wise and seasonal trends
Customer segmentation (New, Returning, Loyal)
Filters for dynamic analysis

📊 Dashboard Highlights
Interactive and user-friendly design
Clear visualization of customer behavior
Drill-down capability for deeper insights
Business-focused KPIs and trends


📈 Key Insights
Customers with higher previous purchases contribute significantly to revenue
Seasonal trends influence purchasing patterns
Discounts and promotions strongly correlate with purchase activity
Certain categories dominate sales performance


📑 Reports & Presentation
Created a structured analytical report summarizing findings
Designed a professional presentation using Gamma covering:
Problem statement
Approach
Key insights
Business recommendations

🚀 How to Run
Prerequisites
Python (Pandas, SQLAlchemy, database connectors)
PostgreSQL / MySQL / SQL Server
Power BI Desktop
Steps
Clone the repository
Place the dataset (customer_shopping_behavior.csv) in the project folder
Run the Jupyter Notebook for:
Data cleaning
Feature engineering
Update database credentials in the script
Load data into SQL database using SQLAlchemy
Run SQL queries for analysis
Open Power BI file to explore the dashboard
Review report and presentation for final insights
