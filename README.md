# Retail Customer Behaviour Analytics

An end-to-end data analytics project analyzing retail customer behavior — from raw data to an interactive Power BI dashboard.

## Overview
This project explores customer purchasing patterns, demographics, and spending habits for a retail business. It covers the full analytics workflow: loading and cleaning data in Python, exploratory data analysis (EDA), querying with SQL, and visualizing insights in an interactive Power BI dashboard.

## Dataset
Retail customer transaction data including customer demographics (age, gender), purchase amount, product category, subscription status, shipping type, review ratings, and location.

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib/Seaborn) — data loading, cleaning, EDA
- **SQL** (PostgreSQL / MySQL / SQL Server) — querying and aggregations
- **Power BI** — interactive dashboard
- **Gamma** — presentation/report generation

## Project Steps
1. **Load Data** — Imported the raw dataset into Python for initial inspection.
2. **Exploratory Data Analysis** — Analyzed distributions, trends, and relationships across customer attributes.
3. **Data Cleaning** — Handled missing values, duplicates, and inconsistent formatting to prepare a clean dataset.
4. **SQL Analysis** — Wrote queries to aggregate and extract business insights from the cleaned data.
5. **Dashboard Build** — Designed an interactive Power BI dashboard with filters for subscription status, gender, age group, and shipping type.
6. **Reporting** — Summarized key findings into a report and presentation (built with Gamma).

## Dashboard
![Retail Customer Behaviour Analytics Dashboard](dashboard.png)

The dashboard provides a snapshot of customer behavior and includes:
- **Number of Customers**, **Average Purchase Amount**, and **Average Review Rating** as headline metrics
- **% of Customers by Subscription Status** (donut chart)
- **Revenue by Category** and **Sales by Category** (bar charts)
- **Salary by Age Group** and **Revenue by Location** (comparison charts)
- Interactive filters: Subscription Status, Gender, Age Group, and Shipping Type

## Results
- **599** total customers analyzed
- **$60.26** average purchase amount
- **3.79** average review rating
- Only **4.38%** of customers are active subscribers, indicating room to grow subscription enrollment
- **Clothing** drives the most revenue and sales volume, followed by Accessories, Footwear, and Outerwear
- Purchase behavior and salary distribution vary noticeably across age groups and states

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/AGupta-23/Retail-Customer-Behaviour-Analytics.git
   ```
2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebooks in `/notebooks` to reproduce data cleaning and EDA.
4. Execute the scripts in `/sql` against your PostgreSQL/MySQL/SQL Server instance to reproduce the query-based analysis.
5. Open the `.pbix` file in Power BI Desktop to explore the dashboard.
