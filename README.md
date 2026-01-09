# 📊 Customer Shopping Behavior Analysis & Insights Dashboard

---

## 🧾 Project Overview

This is an **end-to-end Data Analyst portfolio project** that analyzes customer shopping behavior using transactional retail data.  
The project focuses on identifying **customer trends, revenue patterns, and subscription insights**, and presents results through:

- **SQL analysis (MySQL)**
- **Interactive Power BI dashboard**
- **Business presentation created using Gamma AI**

---

## 🎯 Project Objectives

- Analyze customer purchasing behavior  
- Identify high-revenue customer segments  
- Compare subscribers vs non-subscribers  
- Evaluate product and category performance  
- Support business decision-making with data  

---

## 📂 Dataset Details

| Attribute | Description |
|---------|-------------|
| Total Records | 3,900 |
| Total Columns | 18 |
| Domain | Retail / E-commerce |
| Missing Values | Review Rating column |

---

## 🧹 Data Cleaning & Preparation (Python)

The dataset was cleaned and prepared using **Python (pandas)**.

### Steps Performed
- Loaded dataset and inspected structure  
- Checked summary statistics  
- Handled missing values using **median imputation**  
- Standardized column names (**snake_case**)  
- Feature engineering:
  - Created `age_group`
  - Derived purchase frequency features  
- Removed redundant columns  
- Exported cleaned data for SQL analysis  

---

## 🗄️ Data Analysis Using MySQL

The cleaned dataset was loaded into **MySQL**, and business-focused SQL queries were written to extract insights.

### Key Analyses Performed
- Revenue by gender  
- Subscriber vs non-subscriber spending  
- High-spending customers using discounts  
- Top-rated products  
- Revenue and sales by category  
- Shipping type impact on purchase amount  
- Customer segmentation:
  - New  
  - Returning  
  - Loyal  
- Revenue contribution by age group  

---

## 📊 Power BI Dashboard

An interactive dashboard was created to visualize insights.

### Key KPIs
- Total Customers  
- Average Review Rating  
- Average Purchase Amount  

### Visualizations
- Revenue by category  
- Sales by category  
- Revenue by age group  
- Sales by age group  
- Subscription status distribution  

### Filters
- Subscription Status  
- Gender  
- Product Category  
- Shipping Type  
<img width="1004" height="618" alt="image" src="https://github.com/user-attachments/assets/b941451b-3e74-4cac-a108-17298d9f4efd" />

---

## 📽️ Business Presentation (Gamma AI)

A professional presentation was created using **Gamma AI** to communicate insights to non-technical stakeholders.

### Presentation Includes
- Project overview  
- Key findings  
- Customer behavior trends  
- Revenue insights  
- Business recommendations  

---

## 💡 Key Insights

- Subscribers have a higher average purchase value  
- Certain categories contribute significantly to total revenue  
- Younger age groups generate higher sales volume  
- Express shipping users spend more per order  
- Loyal customers show strong repeat purchase behavior  

---

## 🛠️ Tools & Technologies Used

- **Python** – Data cleaning & EDA  
- **Pandas, NumPy** – Data manipulation  
- **MySQL** – SQL analysis  
- **Power BI** – Data visualization  
- **Gamma AI** – Business presentation  
- **Excel** – Initial data inspection  

---

## 📁 Project Structure
```
├── data/
│ └── customer_shopping_data.csv
├── notebooks/
│ └── data_cleaning_analysis.ipynb
├── sql/
│ └── analysis_queries.sql
├── dashboard/
│ └── Customer_Behavior_Dashboard.pbix
├── presentation/
│ └── Customer_Behavior_Analysis_GammaAI.pptx
└── README.md
```


---

## 🚀 How to Run the Project

1. Perform data cleaning using the Python notebook  
2. Load cleaned data into MySQL  
3. Execute SQL queries for analysis  
4. Open Power BI dashboard to explore insights  
5. Use Gamma AI PPT for business presentation  

---

## 📄 License

This project is created for **learning, academic, and portfolio purposes**.
