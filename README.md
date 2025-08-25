# 🚖 Z-Score-Based Ride Analytics

A **Power BI dashboard project** analyzing ride booking behavior and efficiency across airport pickup points in **Bangalore**, segmented by **peak** and **non-peak** hours.

---

## 📌 Project Overview
**AeroCab** operates cab services from five major airport pickup points. To ensure service efficiency, the company wants to understand the **ride booking flow** and identify **performance gaps** between:

- **Peak Hours**: 5–9 AM, 6–11 PM  
- **Non-Peak Hours**

This project delivers:

- 🔄 Full ETL pipeline in Power BI  
- 📊 Analysis of booking efficiency metrics  
- 📉 Outlier detection using Z-score analysis  
- 🔍 Filtering for normal vs. outlier-influenced data  
- 📈 Interactive dashboards for performance comparisons  

---

## 🛠 ETL Process
- **Extract**: Loaded raw ride data into Power BI  
- **Transform**:  
  - Calculated key metrics: **ABT, ACT, ABOT**  
  - Derived **Z-scores** for booking outcome time  
  - Binned Z-scores into **0.20 ranges**  
  - Labeled **Z > 2 as Outliers**, **≤ 2 as Normal**  
- **Load**: Built relationships & developed custom dashboards  

---

## 📊 Metrics Tracked
| Metric | Description |
|--------|-------------|
| **Total Rides** | Number of ride requests |
| **Confirmed Rides (%)** | Booking success rate |
| **Unconfirmed Rides (%)** | Booking failures |
| **ABT** | Average Booking Time |
| **ACT** | Average Cancellation Time |
| **ABOT** | Average Booking Outcome Time |
| **Z-Score Binning** | Grouped into 0.2 ranges to analyze outlier impact |

---

## 🔍 Key Insights
- **Peak Hour Efficiency**: Certain pickup zones show higher confirmation rates during peak hours.  
- **Outlier Impact**: Rides with **Z > 2** significantly increase average booking outcome times.  
- **Data Comparison**: Removing outliers improves visibility into operational norms.  
- **Booking Gaps**: Zones with high unconfirmed rates may need **process redesign or staffing changes**.  

---

## 📊 Dashboard Features
- KPI filters by:  
  - Pickup Area  
  - Peak vs. Non-Peak  
  - Outlier vs. Normal rides  
- Distribution of Z-score bins  
- Comparison view **before vs. after outlier removal**  
- Interactive visual filters for easy exploration  

---
---

## 🧰 Tools & Techniques
- **Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Z-Score Outlier Detection**  
- **ETL Process Modeling**  
- Visuals: KPI Cards, Line & Bar Charts, Filters  

---

## 📈 Business Value
- 🧠 Identify **zones & hours with low booking success**  
- 🚫 Detect & analyze **impact of anomalous bookings**  
- ⏱ Improve **operational efficiency** (ABT, ABOT, ACT)  
- 🗺 Optimize **fleet allocation** during peak hours  

--- 
