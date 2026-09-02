# E-Commerce Customer Segmentation & Behavioral Analytics

## 📌 Business Overview
This project provides an end-to-end exploratory data analysis (EDA) and RFM (Recency, Frequency, Monetary) customer segmentation for a UK-based online retail dataset containing over 500,000 transaction records.

The primary goal is to transform raw transactional logs into actionable marketing and supply chain strategies—identifying key customer tiers, churn risks, and top revenue drivers to maximize Customer Lifetime Value (CLV).

---

## 🛠️ Tools & Technologies Used
* **Language:** Python
* **Data Manipulation:** pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Environment:** VS Code, GitHub Codespaces
* **Methodology:** RFM Analysis, Quantile Scoring, Cohort Breakdown

---

## 📊 Key Findings & Insights

1. **Product & Market Performance:**
   * Non-product administrative entries (e.g., POSTAGE, Manual fees) were filtered out to ensure true product sales trends.
   * Top international revenue markets (excluding the UK) include the **Netherlands**, **EIRE (Ireland)**, and **Germany**.
   * Top revenue-generating items include seasonal and home decor products like the *Regency Cakestand 3 Tier* and *White Hanging Heart T-Light Holder*.

2. **RFM Segmentation Breakdown:**
   * **Champions / VIPs (612 customers):** Highest average spend (~£7,413) and lowest recency (~7.6 days).
   * **Potential Satisfied (1,688 customers):** Largest volume cohort with steady engagement (~2.08 average orders).
   * **At Risk / Churned (1,050 customers):** Inactive cohort with an average recency of ~248 days requiring re-engagement strategies.

---

## 🎯 Executive Action Plan

* **VIP Loyalty Program:** Establish exclusive perks, early inventory access, and holiday bundles for top 612 VIP customers.
* **Automated Win-Back Campaign:** Deploy targeted email sequences with limited-time discounts to reactivate the 1,050 At-Risk/Churned accounts.
* **Supply Chain Preparedness:** Scale up inventory replenishment for top physical revenue drivers starting in August/September ahead of Q4 peak demand.

---

## 📂 Project Structure
* `Analysis.ipynb` - Complete Jupyter Notebook containing data cleaning, visual EDA, RFM scoring, and executive summaries.
* `README.md` - Executive summary and project documentation.