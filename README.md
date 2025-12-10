# Customer_Behavior_Analysis

This project delivers a full-stack analytics workflow designed to generate actionable insights from customer shopping behavior. The initiative operationalizes an end-to-end data pipeline—from raw data ingestion to statistical analysis, SQL-driven business queries, and executive-ready dashboards. The goal is to translate behavioral patterns into decision-ready intelligence that informs product strategy, marketing allocation, and customer retention plays.

---

## **📌 Project Overview**

The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

✅ Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

✅ Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually communicates insights and actionable recommendations to stakeholders.

---

## **Tools & Technologies**

**Programming & Analytics:**

* Python 
* Jupyter Notebook

**Database & Querying:**

* PostgreSQL 
* SQL 

**Visualization & Reporting:**

* Power BI (Interactive dashboard)
* Gamma.app (Automated PPT generation)
* PDF reporting

**Version Control:**

* Git / GitHub

---

## **Project Workflow**

This project follows a structured analytics lifecycle to ensure repeatable, scalable insights.

### **1. Data Loading**

* Imported dataset using Pandas.
* Executed schema review using `df.info()`, `df.head()`, and descriptive statistics.

### **2. Exploratory Data Analysis (EDA)**

* Identified data types, distributions, outliers, missing values.
* Visual profiling to assess revenue trends, discount patterns, rating distributions, and customer behavior clusters.

### **3. Data Cleaning**

* Imputed missing review ratings using category-wise medians.
* Standardized column naming to snake_case for consistency.
* Removed redundant fields (e.g., promo_code_used).
* Validated categorical values and normalized outputs.

### **4. Feature Engineering**

* Created **age_group** bins for segmentation.
* Derived **purchase_frequency_days** based on available purchase history.
* Built behavior categories to support targeted SQL analysis.

### **5. SQL-Driven Analytics**

Executed structured business queries on PostgreSQL Server to derive:

* Revenue split by multiple demographic slices
* Discount-based behavioral performance
* Category-wise top products by volume and rating
* Customer segmentation (New, Returning, Loyal)
* Subscription likelihood among high-frequency buyers
* Shipping performance (Standard vs Express)

SQL scripts included in:
`Customer_Shopping_Behavior_Analysis_SQL_Queries.sql`

### **6. Power BI Dashboard Development**

Delivered an interactive dashboard highlighting:

* Revenue trends
* Purchase drivers
* Discount-dependent product performance
* Segmented customer intelligence
* Subscription and shipping comparisons
* KPI cards, drill-downs, and category slices

Dashboard file:
`customer_behavior.pbix`
<img width="1185" height="645" alt="image" src="https://github.com/user-attachments/assets/49501102-d5d3-4e69-9758-a1d3faf22a21" />


### **7. Reporting & Presentation**

* Generated a comprehensive insights report (PDF).
* Designed an executive-ready PPT through Gamma summarizing KPIs, trends, and recommendations.

Files included:

* `Customer Shopping Behavior Analysis.pdf`
* `Customer_Shopping_Behavior_Analysis_.pptx`

---

## **Results & Insights**

Key business outcomes surfaced from the analysis:

* Gender-based revenue contribution is balanced across segments.
* Specific age groups drive a disproportionate share of revenue.
* Subscribers outperform non-subscribers in both average spend and total revenue.
* Discount-heavy product categories demonstrate high conversion but require margin oversight.
* Loyal customers represent the highest lifetime value; targeted onboarding drives Returning → Loyal migration.
* Certain product categories have consistent top performers, ideal for targeted promotions and inventory planning.

