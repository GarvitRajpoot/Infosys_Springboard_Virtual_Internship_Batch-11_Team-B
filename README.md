# 🍔 FoodTrends: Understanding Customer Preferences in FB

## 📌 Project Overview
**FoodTrends** is a comprehensive Business Intelligence solution designed to analyze over **138,000 transaction records** in the FB. The project aims to bridge the gap between **Customer Demand** (what users order) and **Operational Supply** (how efficiently it is delivered).

By transforming raw transactional data into a robust **Star Schema** data model, this project provides strategic insights into Menu Optimization, Delivery Logistics, and Customer Segmentation to drive revenue growth and operational efficiency.

## 📂 Project Files
This repository contains the following deliverables:
* **`Food_Trend.pbix`**: The main Power BI Dashboard file (`.pbix`) containing all 7 analytical report pages.
* **`Team_Presentation.pptx`**: The complete project presentation deck covering objectives, methodology, and insights.
* **`Team_Members_ppt`**: Folder containing the individual contribution presentations and specific analysis breakdowns:
  * **`Garvit Rajpoot Presentation.pptx`**: Individual contribution slides (Garvit).
  * **`Shashank Singh.pptx`**: Individual contribution slides (Shashank).
  * **`vanshika.pptx`**: Individual contribution slides (Vanshika).
* **`Report.pdf`**: Detailed documentation of the project execution, methodologies, and final outcomes.
* **`dataset`**: Folder containing the raw CSV data files used for analysis.
  * **`fact_orders.csv`**: Primary transactional records.
  * **`fact_order_items.csv`**: Item-level details for every order.
  * **`fact_delivery_performance.csv`**: Logistics data regarding delivery times and delays.
  * **`fact_ratings.csv`**: Customer feedback and ratings.
  * **`dim_restaurant.csv`**: Metadata for restaurant locations and cuisines.
  * **`dim_customer.csv`**: Customer demographic profiles.
  * **`dim_menu_item.csv`**:  Menu categorization and pricing details.
  * **`dim_delivery_partner_.csv`**: Delivery driver information.
  * **`Balaji Fast Food Sales.csv`**: Supplementary sales records.
* **`LICENSE`**: Project usage and distribution rights.
* **`README.md`**: Project documentation (this file).

## ✨ Key Features
* **Interactive Dashboards:** 7 distinct analytical views covering Sales, Menu, Logistics, and Customer Demographics.
* **Star Schema Architecture:** Optimized data model connecting a central Fact table to 5 Dimension tables for accurate cross-filtering.
* **Advanced KPIs:** Custom DAX measures for **SLA Adherence %** (On-Time Delivery), **Customer Retention Rate**, and **Average Order Value (AOV)**.
* **Root Cause Analysis:** AI-driven Decomposition Trees to trace negative sentiment down to specific drivers (e.g., specific cuisines in specific cities).
* **Logistics Command Center:** Real-time tracking of fleet performance, highlighting the critical **39% On-Time Delivery Rate**.

## 🛠️ Tools & Technologies Used
* **Microsoft Power BI:** Primary BI tool used for creating interactive dashboards, data modeling, and performance monitoring.
* **Power Query:** Utilized for ETL processes to clean, transform, and standardize raw data for analysis.
* **DAX (Data Analysis Expressions):** Used to script complex measures, KPIs (e.g., Revenue, Churn), and time-intelligence calculations.
* **Star Schema Modeling:** Structured data into Fact and Dimension tables to optimize query performance and simplify relationships.
* **Excel / CSV:** Served as the raw data format for ingestion and preprocessing before import into Power BI.
* **GitHub:** Managed version control, project documentation, and progress tracking throughout the internship.
* **GitLab:** Acted as a secondary repository for secure backup and collaboration during submission stages.
* **Git & Git LFS:** Handled version history and managed large files (like .pbix) efficiently without performance issues.
* **Microsoft Teams:** Facilitated remote collaboration, mentor reviews, and daily stand-up meetings.
* **PowerPoint & Word:** Used for designing professional presentations and compiling the comprehensive project report.
* **Data Sources:** Real-world datasets sourced from **Kaggle** and **Dataful** to simulate business scenarios.

## 📜 License
This project is licensed under the terms found in the `LICENSE` file within this repository.

## 🧠 Team Learnings & Outcomes
### **Technical Skills**
* Mastered **Data Modeling** by creating active One-to-Many relationships to solve filtering errors.
* Gained proficiency in **Advanced DAX**, writing measures to calculate "Month-over-Month Growth" and "Repeat Customer %".
* Learned **Data Storytelling** techniques to present complex operational data as actionable business insights.

### **Soft Skills**
* **Analytical Thinking:** Translating raw operational data into actionable business strategies.
* **Problem Solving:** Identifying bottlenecks in logistics (Delivery Delays) and proposing data-backed solutions.
* **Data Storytelling:** Transforming complex metrics into a clear, compelling narrative for stakeholders.
* **Collaboration:** Working effectively within a team to integrate individual insights into a cohesive project.
* **Presentation & Communication:** Articulating technical findings to judges/mentors clearly.

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
