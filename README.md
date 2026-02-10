# 🍔 FoodTrends: Understanding Customer Preferences in F&B

## 📌 Project Overview
**FoodTrends** is a comprehensive Business Intelligence solution designed to analyze over **138,000 transaction records** in the Food & Beverage industry. The project aims to bridge the gap between **Customer Demand** (what users order) and **Operational Supply** (how efficiently it is delivered).

By transforming raw transactional data into a robust **Star Schema** data model, this project provides strategic insights into Menu Optimization, Delivery Logistics, and Customer Segmentation to drive revenue growth and operational efficiency.

## 📂 Project Files
This repository contains the following deliverables:
* **`Project File(powerBI)`**: The main Power BI Dashboard file (`.pbix`) containing all 7 analytical report pages.
* **`Group_PPT`**: The complete project presentation deck covering objectives, methodology, and insights.
* **`Team_members_PPT`**: Individual contribution slides and specific analysis breakdowns.
* **`Internship_completion_report`**: Detailed documentation of the project execution, methodologies, and final outcomes.
* **`license`**: Project usage and distribution rights.
* **`readme.md`**: Project documentation (this file).

## ✨ Key Features
* **Interactive Dashboards:** 7 distinct analytical views covering Sales, Menu, Logistics, and Customer Demographics.
* **Star Schema Architecture:** Optimized data model connecting a central Fact table to 5 Dimension tables for accurate cross-filtering.
* **Advanced KPIs:** Custom DAX measures for **SLA Adherence %** (On-Time Delivery), **Customer Retention Rate**, and **Average Order Value (AOV)**.
* **Root Cause Analysis:** AI-driven Decomposition Trees to trace negative sentiment down to specific drivers (e.g., specific cuisines in specific cities).
* **Logistics Command Center:** Real-time tracking of fleet performance, highlighting the critical **39% On-Time Delivery Rate**.

## 🛠 Tools & Technologies
* **Microsoft Power BI Desktop:** Primary tool for dashboard development and visualization.
* **Power Query Editor:** Used for ETL (Extract, Transform, Load) to clean null values and standardize city names.
* **DAX (Data Analysis Expressions):** Used for creating complex calculations and time-intelligence measures.
* **Excel/CSV:** Source data management.

## 📜 License
This project is licensed under the terms found in the `license` file within this repository.

## 🧠 Team Learnings & Outcomes
### **Technical Skills**
* Mastered **Data Modeling** by creating active One-to-Many relationships to solve filtering errors.
* Gained proficiency in **Advanced DAX**, writing measures to calculate "Month-over-Month Growth" and "Repeat Customer %".
* Learned **Data Storytelling** techniques to present complex operational data as actionable business insights.

### **Business Outcomes**
* Identified that **Logistics is the primary bottleneck**, with a 5.7-minute average delay driving customer churn.
* Discovered that **Organic Users (52%)** are the most loyal segment and strongly prefer Vegetarian options.
* Validated that bundling low-margin "Beverages" with main courses is the best strategy to increase profitability.

## 🚀 Future Enhancements
* **Row-Level Security (RLS):** Implement security roles to allow Branch Managers to view only their specific City's data.
* **What-If Parameters:** Add interactive sliders to simulate scenarios (e.g., *"If we increase delivery fees by 10%, how does it affect Order Volume?"*).
* **Mobile Layout:** Design a specific mobile view for Area Managers to monitor live fleet performance on smartphones.
* **Real-Time API Integration:** Connect to live delivery data streams instead of static CSV files.

## 📝 Conclusion
The **FoodTrends** project successfully demonstrated that while the business generates healthy revenue, **Last-Mile Delivery** requires immediate restructuring. The data proves that speed is the strongest predictor of customer satisfaction. By shifting focus from "New Acquisition" to "Retention" of the loyal Organic user base, the business can achieve sustainable growth.

## 👥 Contributors
* **Garvit Rajpoot**
* **Shashank Singh**
* **Vanshika**

## 📎 Notes
* All data used in this file are for educational purposes only.
