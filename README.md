# 🎟️ Marketing Analysis– Business Intelligence Project

## 📁 Project Summary

In this bootcampo project, the company **Showz**, a ticketing company, wants to optimize **marketing spend** using user activity, purchase, and advertising data.

The goal is to understand how users interact with the platform, identify when they convert, how much revenue they generate, and how long it takes to recover customer acquisition costs.

---

## 🎯 Objectives

- Analyze customer behavior across sessions, purchases, and devices
- Evaluate marketing costs, acquisition efficiency, and ROI
- Support decision-making on marketing investments with data

---

## 📊 Key Analysis Areas

### 1. User Engagement (Visits)

- Daily, weekly, monthly active users
- Session count per user and session duration
- User retention and return frequency

### 2. Conversion & Revenue (Orders)

- Time between first visit and first purchase (conversion delay)
- Purchase frequency over time
- Average purchase value and total user revenue (LTV)

### 3. Marketing Performance (Costs)

- Total and per-channel ad spend
- Customer acquisition cost (CAC) by source
- Return on Marketing Investment (ROMI)

---

## 📌 Dataset Overview

### `visits_log_us.csv`
- `uid`: User ID  
- `device`: User device  
- `start_ts`, `end_ts`: Session timestamps  
- `source_id`: Advertising source ID

### `orders_log_us.csv`
- `uid`: User ID  
- `buy_ts`: Purchase timestamp  
- `revenue`: Order revenue

### `costs_us.csv`
- `source_id`: Ad source ID  
- `dt`: Date  
- `costs`: Daily ad spend per source

---

## 📈 Approach

1. **Data Preparation**  
   - Import CSV files  
   - Clean and convert data types  
   - Merge datasets for unified analysis  

2. **Metric Calculations**  
   - User activity and session trends  
   - Conversion delays by cohorts  
   - LTV, CAC, ROMI across sources/devices  

3. **Visualization & Insight Generation**  
   - Time series and bar charts for comparisons  
   - Identify top-performing acquisition sources  
   - Evaluate marketing return over time  

---

## ✅ Outcome

This project aims to answer:
- Which marketing channels are most effective?
- When do users convert, and how valuable are they over time?
- How soon do marketing investments pay off?
- Provide **actionable recommendations** on where and how much to invest in user acquisition.

---

## 🧠 Tools Used

- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Metrics: LTV, CAC, ROMI, Conversion Delay


