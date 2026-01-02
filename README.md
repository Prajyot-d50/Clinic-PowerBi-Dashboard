# 📊 Clinic Appointment & Inventory Dashboard – Business Insights

## Dashboard Overview
<img width="1282" height="732" alt="Screenshot 2026-01-02 153145" src="https://github.com/user-attachments/assets/96dbe5e9-469d-4aeb-9a7e-b2ea9fa2dadb" />

<img width="1288" height="728" alt="Screenshot 2026-01-02 153219" src="https://github.com/user-attachments/assets/4480189a-87ec-4f7e-bb4e-617dfa53b874" />



## 📌 Project Overview
This Power BI dashboard provides end-to-end visibility into **clinic operations** using data **extracted from a SQL database**.

The dashboard enables analysis of:
- Appointment booking & confirmation
- Patient demographics & behavior
- Doctor utilization
- City-wise demand
- Inventory & supply chain performance

All insights are derived from **SQL-based transactional and master data**.

---

## 🗄 Data Source (SQL)
The data used in this project is fetched from a **relational SQL database**, containing:
- Appointment transactions
- Patient master data
- Doctor master data
- Clinic & city mapping
- Inventory requests & stock tables

**Tools Used:**
- SQL Server / MySQL (Data Extraction)
- Power BI (Visualization & Analytics)

---

## 🏥 Appointment & Patient Analysis

### 1️⃣ Appointment Confirmation Funnel
- **Total Slots Booked:** 15,585  
- **Confirmed Appointments:** 46.9%  
- **Not Confirmed:** 53.1%  

**Insight:**  
More than half of appointments are not confirmed, leading to revenue loss and underutilized capacity.

**Business Actions:**
- Automated SMS/WhatsApp confirmation
- City-wise non-confirmation analysis

---

### 2️⃣ New vs Returning Patients
- **New Patients:** 48.7%  
- **Returning Patients:** 51.3%  

**Insight:**  
Strong patient retention indicating service trust.

**Business Actions:**
- Loyalty programs
- Track repeat visit frequency

---

### 3️⃣ Gender Distribution
- **Male:** 57.25%  
- **Female:** 38.34%  
- **Not Provided:** 4.41%  

**Insight:**  
Lower female participation highlights growth opportunity.

**Business Actions:**
- Targeted women healthcare campaigns
- Improve data capture completeness

---

### 4️⃣ Weekday vs Weekend Visits
- **Weekday Visits:** 18,918  
- **Weekend Visits:** 4,691  

**Insight:**  
Weekday-heavy demand indicates unused weekend capacity.

**Business Actions:**
- Weekend discounts
- Optimized doctor scheduling

---

## 📈 Growth & Demand Trends

### 5️⃣ Year-over-Year Patient Growth
- Growth trend exists but fluctuates year-on-year

**Insight:**  
Demand volatility suggests dependency on external factors.

**Business Actions:**
- Track YoY growth %
- Align marketing campaigns with demand dips

---

### 6️⃣ City-wise Patient Distribution
Top cities:
- Mumbai
- Kalyan-Dombivli
- Navi Mumbai
- Pune

**Insight:**  
Urban areas dominate patient demand.

**Business Actions:**
- Increase doctors & inventory in top cities
- Expand outreach in low-performing cities

---

## 👨‍⚕️ Operational Efficiency

### 7️⃣ Doctor & Slot Utilization
- **Total Doctors:** 196  
- **Avg Slot Duration:** 30 minutes  
- **Avg Lead Time:** 3.7 days  

**Insight:**  
Planning efficiency is good, but lead time reduction can improve patient experience.

---

## 📦 Inventory & Supply Chain Analysis

### 8️⃣ Inventory Availability
- **Total Requested Quantity:** 31,167  
- **Pending Requests:** 12,221  
- **Available Stock:** 4,205  

**Insight:**  
Low inventory coverage increases stockout risk.

**Business Actions:**
- SQL-based demand forecasting
- Safety stock implementation

---

### 9️⃣ Request Fulfillment Status
- **Pending:** 58.17%  
- **Dispatched:** 41.82%  

**Insight:**  
High pending rate indicates supply chain delays.

**Business Actions:**
- SLA tracking via SQL queries
- Vendor performance monitoring

---

### 🔟 Clinic-wise Stock Concentration
Top clinics by stock:
- Sarita Vihar – 34%
- Dombivali East – 29%

**Insight:**  
Uneven stock distribution increases operational risk.

**Business Actions:**
- Stock redistribution logic
- Minimum stock alerts

---

## 🎯 Business Outcomes
- Improved appointment confirmation
- Better doctor utilization
- Reduced inventory shortages
- Data-driven city expansion
- Improved patient retention

---

## 🛠 Tech Stack
- **SQL** – Data Extraction, Joins, Aggregations  
- **Power BI** – Data Modeling & Dashboards  
- **DAX** – KPIs & Time Intelligence  

---

## 📌 Use Cases
- Clinic operations monitoring  
- Capacity planning  
- Inventory optimization  
- Patient behavior analysis  

