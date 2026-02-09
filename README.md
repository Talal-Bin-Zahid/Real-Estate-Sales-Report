# Real-Estate-Sales-Report
<img width="958" height="539" alt="Real Estate Sales Report" src="https://github.com/user-attachments/assets/5d9bb646-de09-4f32-b9b2-305250bbf3a0" />

## 📌 Project Overview

This project presents an end-to-end **Real Estate Sales Analytics Dashboard** developed using **Power BI**, analyzing residential property sales data from **July 2014 to April 2015**.

The dashboard is designed to deliver **actionable business insights** into pricing behavior, property characteristics, demand distribution, and profitability. It enables stakeholders to understand **what drives property value**, identify **high-impact features**, and evaluate **overall financial performance** within the real estate market.

The report combines **descriptive analytics**, **trend analysis**, and **feature impact decomposition** to support data-driven decision-making for real estate analysts, investors, and business intelligence professionals.

---

## 🎯 Business Objectives

* Analyze **overall sales performance and profitability**
* Identify **key property attributes** influencing price
* Understand **market demand distribution** across price ranges
* Evaluate the **impact of size, location (waterfront), and quality metrics**
* Track **seasonal price trends** over time
* Provide an interactive tool for **exploratory analysis**

---

## 📊 Key Performance Indicators (KPIs)

The dashboard tracks the following **core business KPIs**, calculated using DAX:

| KPI                            | Description                                    | Value              |
| ------------------------------ | ---------------------------------------------- | ------------------ |
| **Total Sales**                | Total revenue generated from property sales    | **$11.67 Billion** |
| **Average Sale Price**         | Mean selling price across all properties       | **$540.09K**       |
| **Price per Sqft**             | Average price per square foot of living area   | **$259.67**        |
| **Assumed Total Cost**         | Estimated total acquisition / development cost | **$9.34 Billion**  |
| **Total Profit**               | Net profit derived from sales                  | **$2.33 Billion**  |
| **Return on Investment (ROI)** | Profitability ratio: Profit ÷ Cost             | **25.00%**         |

---

## 📈 Analytical Insights & Findings

### 🔹 Pricing & Property Characteristics

* **Property prices increase with bedroom count**, peaking around **7–8 bedrooms**, after which prices gradually decline.
* **Grade** (construction and design quality) is one of the **strongest price drivers**, significantly amplifying average sale value.
* **View and condition** further enhance pricing, particularly for higher-grade properties.

### 🔹 Size & Location Impact

* **Sqft Living shows a strong positive correlation with price**.
* **Waterfront properties** command significantly higher prices for similar living areas compared to non-waterfront homes.
* Despite the premium, **99.25% (21.45K units)** of properties are **non-waterfront**, highlighting a supply-heavy non-waterfront market.

### 🔹 Market Demand Distribution

* Most transactions fall within the **$200K – $600K price range**, indicating a **mid-market dominant demand**.
* Fewer properties exist in ultra-high price ranges, reflecting limited luxury inventory.

### 🔹 Time-Based Trends

* **Seasonal price fluctuations** are visible across months.
* A **notable upward trend** in average prices appears toward **early 2015**, suggesting market strengthening during that period.

### 🔹 Feature Contribution Analysis

* The **Decomposition Tree** visual interactively demonstrates how:

  * **Bedrooms → Grade → View → Condition**
    collectively contribute to changes in **Average Sale Price**.

---

## 📊 Dashboard Visualizations

The Power BI report includes the following visuals:

1. **Average Price by Bedrooms**
   Bar chart illustrating how sale prices vary by bedroom count.

2. **Price vs Sqft Living**
   Scatter plot showing the relationship between property size and price, segmented by **Waterfront vs Non-Waterfront**.

3. **Average Price by Month**
   Line chart capturing seasonal and temporal price movements.

4. **Property Count by Waterfront**
   Donut chart comparing the distribution of waterfront and non-waterfront properties.

5. **Total Units by Price Range**
   Column chart showing demand distribution across predefined price bands.

6. **Decomposition Tree**
   Interactive drill-down explaining price variations by:

   * Bedrooms
   * Grade
   * View
   * Condition

---

## 🗂️ Data Dictionary (Key Fields & Parameters)

| Field Name      | Description                                           |
| --------------- | ----------------------------------------------------- |
| **Bedrooms**    | Number of bedrooms in the property                    |
| **Grade**       | Overall construction and design quality score         |
| **View**        | Quality of the property’s view                        |
| **Condition**   | Physical condition rating of the property             |
| **Sqft Living** | Interior living area in square feet                   |
| **Waterfront**  | Binary indicator (1 = Waterfront, 0 = Non-Waterfront) |
| **Sale Date**   | Date of property sale                                 |
| **Price**       | Final sale price of the property                      |

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop** – Data modeling, visualization, and report development
* **Power Query** – Data cleaning, transformation, and preprocessing
* **DAX (Data Analysis Expressions)** –

  * KPI calculations
  * Profit & ROI measures
  * Aggregations and derived metrics

---

## 📌 Use Cases

This project is well-suited for:

* **Real Estate Market Analysis**
* **Business Intelligence & Analytics Portfolios**
* **Power BI Demonstration Projects**
* **Data Analytics Case Studies**
* **Interview & Resume Showcases**

---

## 📎 Project Highlights

* End-to-end BI solution with **business-focused KPIs**
* Clean, interactive dashboard design
* Strong emphasis on **feature impact analysis**
* Suitable for both **technical and non-technical stakeholders**

---
