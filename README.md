# Marketplace Analytics: Retention, Product-Market Fit & RFM Segmentation

## 📌 Business Context
An early-stage marketplace startup faced stagnant revenue.

A data-driven analysis was conducted to identify growth opportunities and improve key metrics without harming user experience.

---

## 🎯 Goals
The project aimed to answer key product questions:

- Evaluate **monthly retention** using cohort analysis  
- Assess whether the product has **product–market fit**  
- Identify **key metrics** to drive revenue growth  
- Prioritize product hypotheses using the **ICE framework**  
- Define success metrics for future experiments  
- Deliver actionable insights and recommendations  

---

## 📊 Data Description

The analysis is based on marketplace transaction data, including:
- customer information  
- order history and statuses  
- order-level revenue data  

Data is aggregated at the user level for retention and segmentation analysis.

---

## 🧹 Data Preparation
- Merged datasets using `customer_id` and `order_id`
- Filtered out canceled and unavailable orders
- Aggregated data at the **user level**
- Created derived features:
  - order frequency  
  - total revenue per user  
  - recency (time since last purchase)  

---

## 📈 Analysis

### 1. Retention Analysis
- Built monthly cohorts based on first purchase date  
- Calculated retention rates over time  

👉 **Insight:** Retention drops significantly after the first purchase, indicating weak user engagement

---

### 2. Product–Market Fit
- Evaluated repeat purchase behavior  
- Analyzed retention and frequency patterns  

👉 **Conclusion:** No strong product–market fit yet — users do not return consistently  

---

### 3. Key Product Metrics
Identified core metrics for growth:

- Conversion to purchase  
- Retention rate  
- Average order value (AOV)  
- Purchase frequency  
- Customer Lifetime Value (LTV)  

---

### 4. RFM Segmentation

Customers were segmented based on Recency, Frequency, and Monetary metrics.

The analysis highlights differences in user activity and spending behavior, allowing to distinguish between more and less valuable customer groups.

---

### 5. Hypothesis Prioritization (ICE Framework)

👉 Selected the most promising hypothesis for improving retention and revenue  

---

## 🧠 Key Insights

Low retention from month 1 (~3% repeat purchase rate)
- Majority of users make only one purchase
- Weak product–market fit indicated by low repeat behavior
- Revenue stagnation driven by poor retention, not acquisition  

---

## 💡 Recommendations

- Reduce shipment time and improve order processing
- Identify and fix friction points in coustomer journey
- Re-run cohort analysis to measure retention changes

---

## 🛠 Tech Stack
- Python (Pandas, NumPy)
- Data visualization (Matplotlib, Seaborn)
