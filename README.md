# 📊 Retail Customer Profitability & Churn Risk Analysis (RFM-Based)

## 📌 Project Overview

This project analyzes retail transaction data to evaluate revenue concentration, profit dependency, and customer churn risk using an RFM (Recency, Frequency, Monetary) framework.

The objective is to identify high-value customers, quantify financial exposure, and recommend data-driven retention strategies.

---

## 🎯 Business Problem

Retail organizations often focus on revenue growth without understanding:

- How profit is distributed across customers
- How vulnerable profitability is to customer churn
- Which customer segments require retention focus

This project addresses these challenges using structured business analytics and financial risk modeling.

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)
- Data Cleaning & Feature Engineering
- RFM Segmentation
- Profit Concentration Analysis
- Risk Simulation Modeling

---

# 📊 Key Analysis & Results

## 1️⃣ Revenue Concentration (Pareto Analysis)

Top 20% of customers contribute approximately **48% of total revenue**, indicating moderate revenue concentration.

![Revenue Concentration](images/revenue.png)

---

## 2️⃣ Profit Concentration

Top 20% of customers contribute approximately **81% of total profit**, revealing significant profit dependency on a high-value segment.

![Profit Concentration](images/profit.png)

---

## 3️⃣ RFM Segmentation

Customers were segmented using:

- **Recency** – Days since last purchase  
- **Frequency** – Number of unique orders  
- **Monetary** – Total customer spend  

![RFM Table](images/rfm.png)

---

## 4️⃣ Strict Churn Risk Assessment

Using the 75th percentile of Recency (>183 days) to define high-risk inactivity:

Approximately **17–18% of total profit** is exposed to churn risk from high-value inactive customers.

![Churn Risk](images/churn.png)

---

# 🧠 Strategic Insights

- Profit concentration is significantly higher than revenue concentration.
- A relatively small customer segment drives a large portion of company profitability.
- Churn risk must be evaluated using statistically calibrated thresholds.
- Blanket discount strategies may reduce margins without improving long-term retention.

---

# 💡 Strategic Recommendations

- Implement targeted retention strategies for high-value inactive customers.
- Use personalized engagement rather than broad discounting.
- Evaluate retention ROI before campaign deployment.
- Segment customers based on **profit contribution**, not just revenue.

---

# 📈 Business Impact

This analysis demonstrates how data-driven segmentation and financial risk modeling can:

- Protect profit margins
- Improve retention strategy efficiency
- Support executive-level decision-making

---

## 📁 Repository Structure
