# 💊 Pharmacy Business Intelligence & Intelligent Inventory Dashboard

> **An intelligent pharmacy analytics and inventory management system that transforms sales and drug inventory data into actionable business insights.**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-green)
![Inventory Analytics](https://img.shields.io/badge/Inventory-Analytics-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Overview

The **Pharmacy Business Intelligence & Intelligent Inventory Dashboard** is a data-driven application designed to help pharmacies monitor business performance, record sales, analyze profitability, manage drug inventory, and identify products approaching or exceeding their expiration dates.

The system combines:

- 📊 Business Intelligence
- 💊 Pharmacy Inventory Analytics
- 🧾 Sales Recording
- 💰 Revenue & Profit Analysis
- ⚠️ Drug Expiration Monitoring
- 🧠 Rule-Based Intelligent Alerts
- 📈 Interactive Data Visualization

Instead of simply displaying raw data, the system converts pharmacy data into **actionable business information**.

For example, the system can automatically identify drugs that are:

- ⚠️ Already expired
- 🟡 Expiring within 30 days
- 🟢 More than 30 days away from expiration

This helps pharmacy staff prioritize inventory and reduce potential losses from expired products.

---

# 🎯 Project Goals

The main goal of this project is to demonstrate how **data analytics and business intelligence can solve practical pharmacy business problems**.

The system is designed to answer questions such as:

- How much revenue has the pharmacy generated?
- How much profit has been generated?
- What is the expected profit from current inventory?
- How much money is potentially lost because of expired drugs?
- How many drugs have expired?
- Which drugs will expire within the next 30 days?
- Which drugs should be sold soon?
- How are sales affecting the pharmacy's performance?
- What is the current inventory situation?

---

# 🚨 Business Problem

Pharmacies need to manage both **business performance** and **inventory risk**.

Without proper analytics, pharmacy managers may have difficulty identifying:

- Products approaching expiration
- Expired inventory
- Potential financial losses
- Sales performance
- Profitability
- Inventory-related risks

A spreadsheet may contain this information, but manually analyzing it can be time-consuming and error-prone.

This project addresses the problem by bringing **sales analytics, profitability analysis, inventory monitoring, and expiration intelligence into one interactive dashboard.**

---

# 💡 Solution

The application provides a centralized dashboard where pharmacy users can:

1. Record sales
2. Monitor revenue
3. Analyze profit
4. Monitor inventory
5. Track drug expiration dates
6. Identify expired drugs
7. Identify drugs expiring within 30 days
8. Receive actionable expiration recommendations
9. Monitor potential losses from expired inventory
10. Make data-driven business decisions

---

# ⭐ Key Features

## 📊 1. Business Intelligence Dashboard

The main dashboard provides high-level KPIs that summarize pharmacy performance.

### Key Performance Indicators

- 💰 **Total Revenue**
- 📈 **Expected Profit**
- 💵 **Profit**
- ⚠️ **Expired Drug Loss**
- 💊 **Total Drugs**
- ⏳ **Drugs Expiring Within 30 Days**
- ❌ **Total Expired Drugs**

The KPIs are automatically calculated from the underlying sales and inventory data.

---

## 🧾 2. Sales Recording System

The application allows users to record pharmacy sales directly from the interface.

A sales record can include information such as:

- Drug name
- Quantity sold
- Selling price
- Purchase price
- Sale date
- Revenue
- Profit

After a sale is recorded, the relevant calculations and dashboard metrics can be updated based on the application's data-processing logic.

## Important Disclaimer
This project is a portfolio and business intelligence demonstration system.
It is not intended to replace professional pharmacy management systems, regulatory requirements, pharmaceutical inventory procedures, or professional judgment.
The expiration alerts are based on predefined business rules and should be validated against the pharmacy's actual operational and regulatory requirements before production use.

### 👨‍💻 About the Developer
This project was developed as part of a practical Data Analytics, Business Intelligence, and Data Science portfolio.
The project demonstrates skills in:
- Python
- Data Analysis
- Pandas
- Data Cleaning
- Business Intelligence
- KPI Development
- Data Visualization
- Business Logic
- Inventory Analytics
- Rule-Based Intelligent Systems
- Dashboard Development
- Streamlit
- Data-Driven Decision Making
  
The overall development approach focuses on solving real-world business problems with data and technology.

### Data Flow

```text
New Sale
   │
   ▼
Sales Record
   │
   ▼
Data Processing
   │
   ▼
Business Calculations
   │
   ├───────────────┐
   ▼               ▼
Revenue          Profit
   │               │
   └───────┬───────┘
           ▼
     BI Dashboard
