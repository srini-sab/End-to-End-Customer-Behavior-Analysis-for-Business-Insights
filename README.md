📊 Customer Behavior Dashboard

An end-to-end data analytics project that analyzes customer shopping behavior and purchasing patterns using Python, SQL, Power BI, and a presentation created with Gamma AI.
The project converts raw transactional data into clear insights and communicates findings through both an interactive dashboard and a professional presentation.

📌 Project Overview

This project analyzes customer shopping behavior using data from 3,900 customer purchases across multiple product categories.
The objective is to understand:

Customer demographics

Subscription behavior

Product performance

Revenue and sales trends

The insights are presented through:

An interactive Power BI dashboard

A business-ready PPT created using Gamma AI

📂 Dataset Summary

Total Records: 3,900

Total Columns: 18

Key Features

Customer demographics: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Purchase Amount

Shopping behavior: Discount Applied, Review Rating, Shipping Type

Historical behavior: Previous Purchases, Purchase Frequency

Data Quality

Missing values in Review Rating

Handled using median imputation by product category

🧪 Exploratory Data Analysis (Python)

Data preparation and EDA were performed using Python:

Data loading and inspection using pandas

Summary statistics and structure checks

Missing value handling

Column name standardization (snake_case)

Feature engineering:

age_group

purchase frequency metrics

Removal of redundant columns

Exported cleaned data to PostgreSQL for SQL analysis

🗄️ Data Analysis (SQL)

Business-driven queries were written in PostgreSQL to answer key questions:

Revenue by gender

Subscriber vs non-subscriber spending

High-spending customers using discounts

Top-rated products

Sales and revenue by category

Shipping type impact on revenue

Customer segmentation (New, Returning, Loyal)

Revenue contribution by age group

📊 Power BI Dashboard

The interactive dashboard includes:

KPIs

Number of Customers

Average Review Rating

Average Purchase Amount

Visual Insights

Revenue by category

Sales by category

Revenue by age group

Sales by age group

Subscription status distribution

Filters

Subscription Status

Gender

Product Category

Shipping Type

📽️ Business Presentation (Gamma AI)

To effectively communicate insights to non-technical stakeholders, a professional presentation was created using Gamma AI.

Presentation Highlights

Project objective and dataset overview

Key customer behavior insights

Revenue and sales trends

Subscription and age-group analysis

Actionable business recommendations

This PPT complements the Power BI dashboard by summarizing findings in a storytelling format suitable for business meetings and reviews.

💡 Business Insights & Recommendations

Promote subscription plans with exclusive benefits

Introduce loyalty programs for repeat customers

Optimize discount strategies to balance sales and profit

Focus marketing efforts on high-revenue age groups

Highlight top-rated and best-selling products

🛠️ Tools & Technologies

Python – Data cleaning & EDA

Pandas, NumPy – Data manipulation

PostgreSQL – SQL-based business analysis

Power BI – Interactive dashboard

Gamma AI – Business presentation (PPT)

Excel – Initial data inspection

📁 Project Structure
├── data/
│   └── customer_shopping_data.csv
├── notebooks/
│   └── data_cleaning_analysis.ipynb
├── sql/
│   └── business_queries.sql
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
├── presentation/
│   └── Customer_Behavior_Analysis_GammaAI.pptx
├── README.md

🚀 How to Use

Run the Python notebook for data cleaning and EDA

Load cleaned data into PostgreSQL

Execute SQL queries for business insights

Explore the Power BI dashboard

Use the Gamma AI PPT for presentations and reporting

📷 Dashboard Preview
<img width="1080" height="618" alt="image" src="https://github.com/user-attachments/assets/41f2f913-febd-4f0c-a1e7-ff16f4412a76" />

📄 License

This project is created for educational, learning, and portfolio purposes.
