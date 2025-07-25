# 📊 E-commerce Sales Analysis & Recommendation Dashboard

This project analyzes real-world transaction data from a UK-based online retailer, using the "Online Retail Dataset" published on the UCI Machine Learning Repository. Covering ~500,000 transactions from Dec 2010–Dec 2011, the project explores sales trends, top products, customer purchase patterns, and applies market basket analysis to recommend product bundles.

---

## 📌 Objectives
✅ Identify sales trends and seasonal effects  
✅ Discover top-selling products and key customer segments  
✅ Perform market basket analysis to recommend frequently bought-together products  
✅ Build an interactive dashboard to present insights visually

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Power BI  for dashboard
- Jupyter Notebook for data exploration

---

## 🛠 Project Steps
1. Data cleaning: handle missing values, remove invalid transactions, fix data types
2. Exploratory Data Analysis (EDA): visualize sales by month, product, and country
3. Power BI Dashboard : (Top selling products, Orders by country, Daily revenue over time)

---

## 📊 Key Insights
- Top products drive significant revenue share
- UK is the primary market, but there are sales from other countries
- Daily revenue shows patterns useful for campaign planning

---

## 📂 Project Structure
```plaintext
data/                # raw and cleaned datasets
notebooks/           # Jupyter notebooks for each analysis stage
dashboard/           # Power BI / Tableau file
images/              # saved plots and visuals
README.md            # project documentation

---

## ✅ Current Progress
- [x] Data cleaning & preprocessing in Python (Jupyter Notebook)
- [x] Exploratory Data Analysis (EDA) with matplotlib & seaborn
- [x] Created interactive Power BI dashboard showing:
  - Top selling products
  - Orders by country (map)
  - Daily revenue trends

---

## 📍 Details of what’s done
- Loaded first 5000 rows from **Online Retail.xlsx**
- Dropped rows with missing product descriptions
- Calculated total revenue (`TotalPrice = Quantity × UnitPrice`)
- Visualized:
  - Top 10 products by quantity sold
  - Top countries by order count
  - Daily revenue trend
- Exported cleaned dataset as **Online_Retail_Clean.csv**
- Built Power BI dashboard: fully interactive with filters and linked visuals
---

## 🙌 Contributor
- Gyanshu Shandilya

---

## 📄 License
Free to use for educational and learning purposes.






