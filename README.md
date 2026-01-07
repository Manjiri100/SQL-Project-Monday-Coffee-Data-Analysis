# ☕ SQL Project: Monday Coffee Data Analysis  

## 📌 Objective  
The goal of this project is to analyze **Monday Coffee’s sales data** (an online coffee seller operating since January 2023) and recommend the **top three major cities in India** for opening new physical coffee shop locations. The analysis focuses on **consumer demand, sales performance, and customer behavior**.  

---

## 🛠️ Activities  

### 1️⃣ Data Loading  
- Designed and created relational tables: **Customers, Products, Sales**.  
- Added **foreign keys** to maintain referential integrity.  
- Created a **trigger** to auto-calculate `TotalAmount` in the Sales table.  

### 2️⃣ Data Cleaning & Preprocessing  
- Checked for **null values** in customer attributes.  
- Identified and handled **duplicate entries**.  
- Validated consistency between `TotalAmount` and `Price × Quantity`.  

### 3️⃣ Data Transformation & Integration  
- Used **joins** to combine Customers, Products, and Sales into a single view for reporting.  
- Applied string functions to split full names into **FirstName** and **LastName**.  

### 4️⃣ Data Analysis & Aggregation  
Performed multiple aggregations to gain insights:  
- 📍 **Total Sales per City**  
- 🧾 **Total Transactions per City**  
- 👥 **Unique Customers per City**  
- 💰 **Average Order Value per City**  
- ☕ **Product Demand per City**  
- 📈 **Monthly Sales Trends**  
- ⭐ **Customer Rating Analysis**  

### 5️⃣ Decision-Making & Recommendations  
- Identified **Top 3 Cities** by sales, order volume, and unique customers.  
- Recommended an **expansion strategy** focusing on:  
  - High-potential cities  
  - Product demand insights  
  - Enhancing customer experience  
  - Seasonal demand alignment  
  - Data-driven pilot store rollouts  

---

## 📊 Key Insights  
- Certain cities show **consistently high sales, unique customers, and order counts**, making them ideal expansion locations.  
- **Product preferences** vary by city, requiring **localized inventory management**.  
- Cities with **higher average order values** are better candidates for **premium coffee experiences**.  
- **Monthly sales trends** highlight seasonal peaks that can guide **marketing and promotions**.  

---

## 🚀 Final Recommendations  
- ✅ Open new coffee shops in the **top three high-performing cities**.  
- ✅ Customize product offerings to match **city-specific demand**.  
- ✅ Launch **loyalty programs** in cities with high repeat purchases.  
- ✅ Align store operations with **monthly demand cycles**.  

---

## 🗂️ Tech Stack  
- **SQL (MySQL)** – database design, cleaning, analysis, and reporting  
- **Relational Database Concepts** – primary keys, foreign keys, triggers, constraints  
- **Aggregation & Joins** – for data integration and insights  

---

## 📁 Repository Contents  
- 📜 **SQL Scripts** – Table creation, triggers, cleaning, transformations, analysis queries  
- 📝 **Documentation** – Project objectives, methodology, and recommendations  

---

🔗 This project demonstrates **end-to-end SQL data analysis**, from **database design** → **data cleaning** → **business insights** → **strategic recommendations** for real-world decision-making.  
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/74c7f3bb-9458-4398-8901-ec9695f74337" />
