
# 📊 Customer Churn Analysis – Power BI Project

## 📌 Overview

This project focuses on analyzing customer churn behavior in a telecom company using Power BI. It explores how customer demographics, service usage, billing factors, and contract types influence churn, and provides actionable insights to improve customer retention.

---

## 🎯 Problem Statement

Customer churn is a critical issue in the telecom industry, leading to revenue loss and increased customer acquisition costs.

> **Objective:**
> To analyze customer data and identify key drivers of churn, enabling the business to take proactive retention measures.

---

## 📂 Dataset Description

The dataset contains detailed information about telecom customers, including:

* 👤 **Customer Information:** gender, SeniorCitizen, Partner, Dependents
* 📅 **Tenure:** number of months customer stayed
* 📡 **Services:** PhoneService, InternetService (DSL/Fiber/No), OnlineSecurity, TechSupport, etc.
* 💳 **Billing:** MonthlyCharges, TotalCharges, PaymentMethod, PaperlessBilling
* 📜 **Contract:** Month-to-month, One year, Two year
* ❗ **Target Variable:** Churn (Yes/No)

---

## 🛠️ Tools & Technologies

* Power BI
* Power Query (Data Cleaning & Transformation)
* DAX (Measures & Calculated Columns)

---

## 📊 Dashboards & Analysis

---

### 🔹 1. Customer Demographics Analysis

**Purpose:** Understand customer profile and churn distribution

**Visuals Used:**

* KPI Cards (Total Customers, Churned Customers, Churn Rate, Avg Charges)
* Donut Chart (Gender Distribution)
* Pie Chart (Churn Distribution)
* Line Chart (Churn Rate by Tenure)
* Scatter Plot (Monthly Charges vs Tenure by Gender)
* Bar Chart (Customers by Tenure Groups)

**Key Insight:**

* Customers with **low tenure (0–12 months)** show the highest churn
* Gender has **minimal impact on churn behavior**

---

### 🔹 2. Service Subscription Analysis

**Purpose:** Identify how services impact churn

**Visuals Used:**

* Donut Chart (Phone Service Usage)
* Decomposition Tree (Churn Drivers: InternetService → OnlineSecurity)
* Stacked Column (Internet Service vs Churn)
* Line Chart (Churn Rate by Internet Service)
* Line Chart (Churn Rate vs Total Services Count)

**Key Insight:**

* **Fiber optic users have the highest churn (~42%)**
* Customers without **Online Security & Tech Support** are more likely to churn
* More services → **lower churn probability**

---

### 🔹 3. Contract & Billing Insights

**Purpose:** Analyze financial and contractual impact on churn

**Visuals Used:**

* Contract vs Churn Analysis
* Payment Method vs Churn
* Avg Monthly & Total Charges comparison

**Key Insight:**

* **Month-to-month contracts show highest churn**
* Customers with **higher monthly charges churn more**
* Long-term contracts reduce churn significantly

---

### 🔹 4. Customer Churn Analysis (Advanced)

**Purpose:** Identify high-risk customers and key churn drivers

**Visuals Used:**

* Decomposition Tree (Churn Rate by Contract & Tech Support)
* Treemap (Churn Concentration by Contract & Tenure)
* Bar Chart (Churn Risk Segmentation)
* Bar Chart (Avg Monthly Charges by Churn)

**Key Insight:**

* High churn concentration in **month-to-month + low tenure customers**
* Customers without support services are at **highest risk**
* Higher-paying customers are more likely to churn

---

## 🔍 Key Insights (Overall)

* 🔴 Month-to-month contracts = **highest churn**
* ⏳ Low tenure customers = **highest risk**
* 🌐 Fiber optic users = **high churn segment**
* ❌ Lack of support services = **major churn driver**
* 💰 Higher charges = **higher churn probability**
* 📦 More services = **better retention**

---

## 💡 Business Recommendations

* Offer discounts for **long-term contracts**
* Promote **bundled services (Security + Tech Support)**
* Improve **fiber optic service experience**
* Target **high-risk customers** with retention campaigns
* Encourage **auto-payment methods**

---

## 📈 Project Highlights

* Interactive dashboards with slicers for dynamic filtering
* Advanced visuals:

  * Decomposition Tree 🌳
  * Treemap 📦
  * Scatter Plot 📍
* End-to-end workflow:

  * Data Cleaning → Transformation → Modeling → Visualization

---

## 🧠 Key Learnings

* Identifying churn drivers using real-world data
* Applying DAX for business metrics
* Designing professional dashboards
* Translating insights into business decisions

---

## 📌 Conclusion

This project demonstrates how Power BI can be used to uncover customer behavior patterns and provide actionable insights to reduce churn and improve business performance.

---

## 🚀 Future Scope

* Build a churn prediction model using Machine Learning
* Deploy dashboard to Power BI Service
* Integrate real-time data pipelines
