# Churn Analysis End-to-End

Customer Churn: End-to-End Analytics & Prediction is a comprehensive data portfolio project integrating **SQL Data Engineering**, **Machine Learning**, and **Business Intelligence** to identify historical attrition patterns and predict future customer churn.

---

##  Project Workflow & Architecture

### 1. Data Engineering (MySQL Workbench)
* **ETL Pipeline:** Migrated raw customer data into a staging database, handled null values, and cleaned data types directly via SQL scripts to ensure absolute data integrity.
* **Database Views:** Developed optimized virtual tables (`Views`) to cleanly segment active users, historic churners, and new joiners for downstream analytics.

### 2. Machine Learning Pipeline (Python)
* **Predictive Modeling:** Built and tuned a **Random Forest Classifier** to analyze historical customer behavior and accurately predict future churn risks.
* **Evaluation:** Validated model performance (achieving an overall **84% accuracy**) using Confusion Matrices, Classification Reports (Precision/Recall), and Feature Importance tracking.

### 3. Business Intelligence (Power BI)
* **Data Modeling:** Established a logical schema inside Power BI by connecting directly to the local MySQL database, utilizing custom explicit DAX measures (`Total Customers`, `Total Churn`, `Churn Rate`, `New Joiners`).
* **Executive Summary:** Designed an interactive dashboard highlighting macro-level KPIs alongside demographic, geographic, and account-based trends.
* **Risk Profile Matrix:** Implemented service-level matrices enhanced with visual data bars to pinpoint specific product features driving high customer turnover.
* **Predictive Profiling:** Created a dedicated *Future Churner Profile* view that visualizes the machine learning model's output, giving stakeholders a proactive list of accounts to target with targeted retention campaigns.

##  Tech Stack & Tools

* **Data Engineering & Databases:** MySQL | MySQL Workbench
* **Machine Learning & Data Science:** Python | Jupyter Notebook | Scikit-Learn (Random Forest)
* **Business Intelligence:** Power BI Desktop | DAX 
