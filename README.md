#Customer Shopping Behavior Analysis Dashboard

📌 Overview

This project analyzes customer shopping patterns and presents actionable business insights through an interactive Power BI dashboard.

The objective was to take raw transactional data, clean and analyze it using Python and SQL, and build a dynamic dashboard for decision-making.

This project demonstrates a complete data analytics workflow — from raw data to business insights.

🧰 Tech Stack

* Python – Pandas, NumPy, Matplotlib, Seaborn
* SQL – PostgreSQL / MySQL / SQL Server
* Power BI – Interactive dashboard
* Jupyter Notebook

📂 Dataset

File: `customer_shopping_behavior.csv`

The dataset includes:

* Customer demographics (Gender, Age Group)
* Subscription status
* Product categories (Clothing, Accessories, Footwear, Outerwear)
* Purchase amounts
* Review ratings
* Shipping types


🔎 Project Workflow

1️⃣ Data Preprocessing (Python)

* Loaded dataset using Pandas
* Handled missing values
* Removed duplicates
* Performed data validation and formatting
* Conducted exploratory data analysis (EDA)

2️⃣ SQL Analysis

* Imported dataset into relational database
* Wrote queries to calculate:

  * Total revenue
  * Category-wise revenue
  * Average purchase amount
  * Sales by age group
  * Customer segmentation metrics

3️⃣ Power BI Dashboard Development

Built an interactive dashboard including:

* KPI Cards

  * 3.9K Total Customers
  * $59.76 Average Purchase Amount
  * 3.75 Average Review Rating

* Revenue by Category

* Sales by Category

* Subscription Status Distribution

* Revenue by Age Group

* Sales by Age Group

* Dynamic Filters:

  * Subscription Status
  * Gender
  * Category
  * Shipping Type

📊 Dashboard Preview

<img width="1357" height="744" alt="Screenshot 2026-02-27 224736" src="https://github.com/user-attachments/assets/84e695d6-f7fd-49c2-b90d-58dc7a8c00e0" />

📈 Key Insights

* Clothing generates the highest revenue and sales volume.
* 73% of customers are non-subscribers.
* Young Adults contribute the highest revenue share.
* Average purchase value is approximately $60.
* Customer ratings remain consistently above 3.5.

