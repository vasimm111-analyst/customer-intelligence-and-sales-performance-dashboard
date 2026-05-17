#  Customer Intelligence & Sales Performance Dashboard

> **Advanced Customer Behavior Analysis & Business Intelligence Solution**  
> Transforming raw retail/e-commerce data into actionable business insights using **Python, SQL, and Power BI**.

---

#  Project Overview

This project focuses on analyzing **customer purchasing behavior**, identifying **high-value customers**, and generating **business-driven insights** using a structured retail/e-commerce dataset.

The analysis combines:

• 📊 Exploratory Data Analysis (EDA)  
• 🗄 SQL-Based Business Analysis  
• 📈 Interactive Power BI Dashboards  
• 🧠 Customer Segmentation & Revenue Insights  

---

#  Business Objectives

The project helps businesses:

• ✔ Identify high-value customers  
• ✔ Understand purchasing patterns  
• ✔ Optimize discount strategies  
• ✔ Improve marketing campaigns  
• ✔ Increase Customer Lifetime Value (CLV)  
• ✔ Improve customer retention  

---

#  Business Problem Statement

## How can a retail company understand customer purchasing behavior to:

• Increase revenue  
• Improve customer retention  
• Optimize marketing strategies  
• Enhance customer experience  

---

# 🔍 Problem Breakdown

## 1️⃣ Low Customer Retention

Customers are not purchasing frequently.

### Key Questions

• Who are frequent buyers?  
• Who are one-time buyers?  

---

## 2️⃣ Ineffective Marketing Campaigns

Discounts and promo codes may not be performing effectively.

### Key Questions

• Do discounts increase purchases?  
• Which customers respond to promo codes?  

---

## 3️⃣ Product Demand Analysis

Understanding which products and categories perform best.

### Key Questions

• Which category generates maximum revenue?  
• Which products are top-selling?  

---

## 4️⃣ Payment Behavior Insights

Analyzing customer payment preferences.

### Key Questions

• Which payment methods are preferred?  
• Are digital payments increasing?  

---

## 5️⃣ Seasonal Demand Variation

Understanding seasonal purchasing behavior.

### Key Questions

• Which season drives maximum sales?  
• How does season impact revenue?  

---

## 6️⃣ Customer Segmentation

Identifying different customer types.

### Customer Segments

• High-value customers  
• Frequent buyers  
• Discount-sensitive customers  

---

# 📊 Business Questions Solved

### Revenue & Sales Analysis

• Which category generates the highest revenue?  
• Are discounts increasing purchase value?  
• Revenue contribution by gender  
• Revenue contribution by age group  

### Customer Insights

• Which customers used discounts but still spent above average?  
• Do subscribed customers spend more?  
• Are repeat buyers likely to subscribe?  

### Product Insights

• Top 5 products with highest discount usage %  
• Top & bottom 5 products by review rating  
• Top 3 most purchased products within each category  

### Shipping & Purchase Behavior

• Standard vs Express shipping analysis  
• Average purchase comparison by shipping type  

### Customer Segmentation

• New Customers  
• Returning Customers  
• Loyal Customers  

---

# 🗂 About the Dataset

## Dataset Features

### Numerical Columns

• Age  
• Purchase Amount  
• Previous Purchases  

### Categorical Columns

• Category  
• Payment Method  
• Season  
• Shipping Type  
• Subscription Status  

---

# ⭐ Why This Dataset Matters

## 👑 High-Value Customer Identification

Identify loyal and repeat customers.

## 🛍 Purchase Pattern Analysis

Understand:

• What customers buy  
• How often they purchase  
• Average spending behavior  

## 🎯 Discount Optimization

Improve promotional campaigns and pricing strategies.

## 💰 Customer Lifetime Value (CLV)

Increase long-term customer profitability.

---

# 📘 Data Dictionary

| Column Name | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Age / Gender | Customer demographics |
| Item Purchased | Product purchased |
| Category | Product category |
| Purchase Amount | Amount spent |
| Location | Customer location |
| Size / Color | Product attributes |
| Season | Purchase season |
| Review Rating | Product rating |
| Subscription Status | Subscription membership |
| Shipping Type | Delivery method |
| Discount Applied | Discount usage |
| Previous Purchases | Past purchase count |
| Payment Method | Transaction method |
| Purchase Frequency | Weekly / Monthly etc. |

---

# 🧹 Exploratory Data Analysis (EDA)

## Python Workflow

### ✔ Data Loading

Imported dataset using Pandas.

### ✔ Initial Exploration

Performed:

• Null value checks  
• Data type inspection  
• Statistical summaries  

### ✔ Data Cleaning

Applied:

• Category mapping corrections  
• Smart imputation techniques  
• Duplicate removal  
• Column standardization  

### ✔ Export to SQL

Prepared cleaned dataset for SQL Server & Power BI.

---

# 📈 Key Business Insights

## 🏆 Highest Revenue Generating Category

Identified categories contributing maximum revenue.

### Business Impact

• Better inventory planning  
• Improved product positioning  
• Optimized marketing focus  

---

## 💸 Discount Effectiveness Analysis

Evaluated whether discounts increase spending.

### Business Impact

• Optimize pricing strategies  
• Reduce unnecessary discount dependency  
• Improve profitability  

---

## 👨‍👩‍👧 Revenue Contribution by Gender

Compared spending patterns across customer demographics.

### Business Impact

• Targeted marketing campaigns  
• Better audience segmentation  

---

## 🎯 High-Spending Discount Users

Identified customers who:

• Used discounts  
• Still spent above average  

### Business Impact

• Personalized promotions  
• Increased retention  
• Higher CLV  

---

## ⭐ Product Rating Analysis

Identified:

• Top-rated products  
• Low-performing products  

### Business Impact

• Improve product quality  
• Promote best-performing products  

---

## 🚚 Shipping Behavior Analysis

Compared customer spending across shipping methods.

### Business Impact

• Shipping optimization  
• Encourage premium delivery adoption  

---

## 🔔 Subscriber vs Non-Subscriber Analysis

Compared:

• Average spending  
• Total revenue  

### Business Impact

• Evaluate subscription program effectiveness  
• Improve recurring revenue  

---

## 🏷 Products with Highest Discount Dependency

Analyzed products heavily reliant on discounts.

### Business Impact

• Better pricing optimization  
• Reduced margin loss  

---

## 👥 Customer Segmentation

Segmented customers into:

| Segment | Criteria |
|---|---|
| New Customers | Low previous purchases |
| Returning Customers | Moderate purchase frequency |
| Loyal Customers | High purchase frequency |

### Business Impact

• Personalized campaigns  
• Improved retention strategies  

---

# 🛠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data cleaning & analysis |
| Pandas | Data manipulation |
| SQL Server | Database management |
| T-SQL | Business analysis queries |
| Power BI | Dashboard creation |
| DAX | KPI & calculated measures |
| Jupyter Notebook | Analysis workflow |
| SSMS | SQL execution |

---

# 📁 Project Structure

```bash
Customer-Behaviour-Analysis/
│
├── dataset/
│   └── customer_behaviour_analysis.csv
│
├── sql_queries/
│   └── customer_behaviour_analysis.sql
│
├── notebooks/
│   └── customer_analysis.ipynb
│
├── powerbi/
│   └── customer_behaviour_dashboard.pbix
│
├── screenshots/
│   └── dashboard_screenshot.png
│
├── README.md
└── requirements.txt
```

---

# 📂 Folder Description

| Folder | Description |
|---|---|
| dataset/ | Raw dataset |
| sql_queries/ | SQL analysis queries |
| notebooks/ | Python notebooks |
| powerbi/ | Power BI dashboard |
| screenshots/ | Dashboard images |
| README.md | Project documentation |
| requirements.txt | Python dependencies |

---

# ⚙ How to Run the Project

## Clone the Repository

```bash
git clone https://github.com/rahuldata/Customer-Behaviour-Analysis.git
```

---

# 📸 Dashboard Preview

_Add your Power BI dashboard screenshot here_

```bash
screenshots/dashboard_screenshot.png
```

---

# 🔮 Future Improvements

• Customer churn prediction  
• Recommendation system  
• Advanced customer segmentation using ML  
• Real-time sales dashboard  
• Forecasting future sales trends  

---

# 👨‍💻 Author

## **Vasim Akram**
    vasimakram1110@gmail.com
🔗 LinkedIn: Add Your LinkedIn Profile  
🔗 GitHub: Add Your GitHub Profile  

---

