# Customer_Shopping_Behavior_Analysis
Data Analytics project showcasing Customer shopping behavior using  Python , SQL and Power BI

This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.

This project is perfect for:
- 📊 Data Analyst aspirants who want to build a strong **Portfolio Project** for interviews and LinkedIn
- 📚 Anyone learning Python, SQL, and Power BI
- 💼 Professionals preparing for interviews in Data Analytics, Data Science or Product Analytics roles

## 📌 Project Overview
The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

✅ Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

✅ Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually communicates insights and actionable recommendations to stakeholders.


## 📁 Dataset Summary  

- **Total Records:** 3,900  
- **Total Features:** 18  

### 🔑 Key Features:
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Behavioral Data:** Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type  

- **Data Cleaning:**  
  Missing values in *Review Rating* column were handled using median imputation.

---

## 🧹 Data Preprocessing & Feature Engineering  

- Loaded dataset using **Pandas**  
- Performed data exploration using `.info()` and `.describe()`  
- Handled missing values using category-wise median  
- Renamed columns for better readability (snake_case format)  
- Created new features:
  - `age_group` for customer segmentation  
  - `purchase_frequency_days` for behavioral insights  
- Removed redundant columns after validation  
- Exported cleaned dataset to **PostgreSQL** for further analysis  

---

## 🗄️ Data Analysis (SQL)  

Performed business-driven analysis to extract key insights:

- 📌 Revenue comparison by gender  
- 📌 Identification of high-spending discount users  
- 📌 Top 5 products based on customer ratings  
- 📌 Impact of shipping type on purchase amount  
- 📌 Subscriber vs Non-subscriber analysis  
- 📌 Discount-driven product identification  
- 📌 Customer segmentation (New, Returning, Loyal)  
- 📌 Top 3 products in each category  
- 📌 Repeat purchase vs subscription behavior  
- 📌 Revenue contribution by age group  

---

## 📊 Dashboard (Power BI)  
## 🖼 Dashboard Preview
![Dashboard Screenshot](Customer Shopping.png)

Built an interactive dashboard to visualize:
- Sales performance  
- Customer segmentation  
- Product category insights  
- Purchase trends  

## 🛠️ How to Use This Project

1. **Clone the repository**
      
2. **Open Customer_Shopping_Behavior_Analysis.ipynb notebook**

    This file contains:

      - Data Import

      - Data exploration

      - Data cleaning

      - Connection to SQL Database
  
3. **Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server**

      - Create a database in SQL

      - Run Python code to load data into SQL database
  
      - Open **customer_shopping.sql**
  
      - Answer Business Questions using SQL Queries 
      
4. **Connect the SQL Database to Power BI**

      - Open **Customer Shopping Behaviour.pbix**
   
      - Create interactive dashboard in Power BI
  
---

## 💡 Key Insights  

- High-performing categories contribute significantly to revenue  
- Loyal customers drive a major portion of sales  
- Discounts influence buying behavior but need optimization  
- Subscribers show higher engagement and spending patterns  

---

## 📌 Business Recommendations  

- ✅ Improve subscription benefits to boost retention  
- ✅ Introduce loyalty programs for repeat customers  
- ✅ Optimize discount strategies for better profitability  
- ✅ Promote top-rated and best-selling products  
- ✅ Focus marketing on high-value customer segments  

---

## 🛠️ Tech Stack  

- **Python (Pandas, NumPy)**  
- **SQL (PostgreSQL)**  
- **Power BI**  
- **Matplotlib & Seaborn**  

---

## 🎯 Conclusion  

This project demonstrates strong skills in **data cleaning, analysis, and visualization**. It showcases the ability to transform raw data into actionable insights, making it highly relevant for **Data Analyst roles**.

---

## 🚀 About the Project  

> This project reflects my ability to work with real-world datasets and deliver business-oriented insights using Python, SQL, and Power BI.
