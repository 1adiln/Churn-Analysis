# 📊 Customer Churn Analysis for a Telecom Provider

## 📌 Project Overview
This project analyzes customer churn for a telecom provider using **realistic mock data**.  
The goal is to **identify why customers leave** and provide **actionable strategies** to improve retention.

---

## 🎯 Objectives
- Understand key drivers of churn (e.g., billing, complaints, tenure).
- Build meaningful **features** that strengthen churn prediction.
- Provide clear, actionable **business insights** for retention strategies.

---

## 🔍 Key Steps
1️⃣ **Data Cleaning & Preparation**
- Checked for missing values and handled inconsistencies.
- Verified numeric features (e.g., `Tenure`, `Complaints`, `MonthlyBill`).

2️⃣ **Feature Engineering**
Created strong new features to improve churn insights:
- `BillToTenure` → Customers paying high bills but with short tenure.
- `Complaint*Bill` → High-paying + complaining customers = likely to churn.
- `UnresolvedRate` → How many issues remain unsolved (key frustration driver).

3️⃣ **Analysis**
- Studied trends & patterns in churners vs. non-churners.
- Found that **high complaint rates & low issue resolution strongly link to churn**.

4️⃣ **Insights & Recommendations**
- Improve **customer support & complaint resolution**.
- Offer **retention incentives** to **new, high-bill customers**.
- Use engineered features to **identify at-risk customers early**.
