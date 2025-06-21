# 📦 Flipkart BBD 2024 — Profitability & Sales Intelligence

> A data analytics case study on Flipkart's Big Billion Day 2024 (simulated).  
> Analyze. Visualize. Profit.

---

## 🔍 What is this project?

This is a **real-world style data analytics project** based on a **synthetic dataset of 10,000 Flipkart transactions** during Big Billion Day 2024.  
It answers one big question:

> 💭 “Is Flipkart’s BBD campaign profitable — and where can it optimize?”

---

## 🧠 What you'll learn from this repo

✅ How to analyze eCommerce profitability  
✅ Which categories & cities drive revenue  
✅ What delivery times reveal about logistics  
✅ How to build a sales intelligence dashboard in Power BI  
✅ How to structure a portfolio-ready GitHub project

---

## 🛠️ Tech Stack

| Area                | Tools Used                        |
|---------------------|------------------------------------|
| Data Analysis       | Python, Pandas                    |
| Data Visualization  | Seaborn, Matplotlib               |
| Dashboarding        | Power BI (.pbix file)             |
| Report Format       | Jupyter Notebook, Word/PDF        |


---

## 📈 Key Business Insights

- 🥇 **Mobiles** drive the highest revenue (but also the highest discounts)
- 🏙️ Top cities: **Mumbai**, **Delhi**, **Bengaluru**
- 💳 **UPI (40%)** and **Credit Cards (25%)** dominate payments
- 📉 Estimated **net profit margin** ≈ 15% post discount
- ⏱️ **Furniture** has longest delivery times (~6–8 days)
- ⚡ 70% of revenue comes in the **first 3 days** of the sale

---

## 🎨 Dashboard Preview

> Interactive Power BI dashboard included in `/dashboards` folder.

Highlights:
- Daily Sales Trends 📈  
- Revenue by Category and City 🏷️  
- Delivery Time Analysis 📦  
- Payment Mode Breakdown 💳  
- Dynamic filters (City, Category, Date, Method) 🔍  

*Power BI (.pbix) version available. Ask for a Looker Studio version if preferred.*

---

## 🧪 About the Dataset

A synthetic dataset of 10,000 BBD orders. Each row includes:

- Product details (category, price, discount)
- Customer & city
- Final price paid
- Delivery days
- Payment method

👉 Designed to mimic real-world transaction patterns seen in Indian eCommerce.

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yashbhilare21/flipkart-bbd-analysis-2024.git

# Open Jupyter notebook
cd notebooks/
jupyter notebook bbd_eda.ipynb
