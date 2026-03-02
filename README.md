# 📊 Retail Customer Profitability & Churn Risk Analysis (RFM-Based)

## 📌 Project Overview

This project analyzes retail transaction data to evaluate revenue concentration, profit dependency, and customer churn risk using an RFM (Recency, Frequency, Monetary) framework.

The objective is to identify high-value customers, quantify financial exposure due to churn risk, and recommend data-driven retention strategies.

---

## 🎯 Business Problem

Retail organizations often focus heavily on revenue growth without fully understanding:

- How profit is distributed across customers
- How vulnerable profitability is to customer churn
- Which customer segments require retention focus

This project addresses these questions through structured business analytics and financial risk modeling.

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)
- Data Cleaning & Feature Engineering
- RFM Segmentation
- Profit Concentration Analysis
- Risk Simulation Modeling

---

## 📊 Key Analysis & Findings

### 1️⃣ Revenue Concentration (Pareto Analysis)
- Top 20% of customers contribute approximately **48% of total revenue**.
- Revenue distribution is moderately concentrated.

### 2️⃣ Profit Concentration
- Top 20% of customers contribute approximately **81% of total profit**.
- Profitability is highly concentrated among high-value customers.

### 3️⃣ Churn Risk Assessment (RFM-Based)

Customers were segmented using:

- **Recency** – Days since last purchase  
- **Frequency** – Number of unique orders  
- **Monetary** – Total customer spend  

A statistically grounded churn threshold was defined using the 75th percentile of Recency (>183 days).

### 4️⃣ Financial Risk Exposure

- Approximately **17–18% of total profit** is associated with high-value customers who have not purchased in over 183 days.
- Losing this segment would significantly impact overall profitability.

---

## 🧠 Strategic Insights

- Profit concentration is significantly higher than revenue concentration.
- A relatively small customer segment drives a large portion of company profit.
- Churn risk must be evaluated using statistically calibrated thresholds.
- Blanket discount strategies may reduce margins without improving long-term retention.

---

## 💡 Strategic Recommendations

- Implement targeted retention strategies for high-value inactive customers.
- Use personalized engagement instead of blanket discounting.
- Evaluate campaign ROI before deployment.
- Segment customers by **profit contribution**, not just revenue.

---

## 📈 Business Impact

This analysis demonstrates how data-driven customer segmentation and financial risk modeling can:

- Protect profit margins
- Improve retention strategy efficiency
- Support executive-level decision making

---

## 📁 Repository Structure

## 📊 Key Results

### Revenue Concentration
![Revenue](images/revenue.png)

### Profit Concentration
![Profit](images/profit.png)

### Strict Churn Risk
![Churn Risk](images/churn.png)

### RFM Segmentation Preview
![RFM Table](images/rfm.png)
