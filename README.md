# customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python sql and power Bi.

 Overview

This project demonstrates a complete data analytics workflow, starting from raw data ingestion in Python to building insights through EDA, SQL analysis, Power BI dashboards, and a final presentation created using Gamma.
It highlights practical skills in data preparation, visualization, database querying, and business storytelling.

📂 Dataset

Source: (Add link or mention if synthetic/mock data)
ype: CSV / Excel
Content: Includes customer behavior, purchase patterns, product categories, subscription details, discounts, ratings, and transaction history.
Goal: Understand customer behavior, identify trends, and generate business insights.


🛠 Tools & Technologies**

Python:** Pandas, NumPy, Matplotlib/Seaborn
SQL Databases: PostgreSQL / MySQL / SQL Server
Power BI:Interactive dashboard development
Gamma App: Automated PPT generation
upyter Notebook: Data exploration environment
Git & GitHub: Version control


📈 Project Steps**

1. Load Dataset in Python

Imported dataset using `pandas.read_csv()`
Performed shape, datatype, null value, and summary checks
created initial visualizations to understand distributions

2. Exploratory Data Analysis (EDA)**

Identified patterns in customer demographics, purchases, shipping types, review ratings, and subscriptions
Detected outliers and anomalies
Analyzed correlations and category-wise behaviors

3. Data Cleaning**

Filled or removed missing values
Handled duplicates
Corrected inconsistent formats (dates, categories, booleans)
Areated new engineered features for deeper insights

4. SQL Analysis**

Cleaned data pushed into SQL database
Ran analytical queries such as:

Revenue comparisons
Segment-wise customer analysis
Discount behavior
Category and product trends
Window functions for ranking

Your SQL queries are stored in:
📄 /customer_behavior_sql_queries.sql`

5. Power BI Dashboard**

Connected dataset to Power BI
Built visuals such as:

Revenue KPIs
Customer segmentation
Product/category analysis
Discount impact trends
Shipping comparison charts
Added filters, drill-downs, and interactive navigation

6. Insights Report

Summarized EDA and SQL findings
Highlighted growth opportunities, top products, and customer trends
Explained business impact with visuals

7. Final PPT using Gamma**

Created a clean, modern presentation covering:

Problem statement
Approach
Insights
Dashboard snapshots
Recommendations



Dashboard Preview

(Add a screenshot here once ready)


📁 Project Structure

```
📦 Data-Analytics-Project
 ┣ 📂 data
 ┣ 📂 notebooks
 ┣ 📂 sql
 │   ┗ customer_behavior_sql_queries.sql
 ┣ 📂 powerbi_dashboard
 ┣ 📂 reports
 ┣ 📂 presentation
 ┗ README.md
```

---

🚀 How to Run the Project

1. Clone Repository**

```bash
git clone <repo-url>
cd Data-Analytics-Project
```

2. Install Python Dependencies

```bash
pip install -r requirements.txt
```
3. Run Jupyter Notebook

```bash
jupyter notebook
```

4. Execute SQL Scripts
AImport cleaned dataset into SQL database (PostgreSQL/MySQL/SQL Server)
Run queries from the `sql` folder

5. View Power BI Dashboard

Open `.pbix` file inside the Power BI directory

6. Check Reports & Presentation
Reports in `/reports`
Final Gamma presentation in `/presentation`


 Results & Key Insights

 Identified customer behavior trends
 Visualized KPIs and revenue metrics
Revealed high-performing products and age groups
Showed the effect of discounts and subscription
 Built an actionable dashboard and business report

---

If you want, I can also:
Generate a requirements.txt
Add sample EDA Python code
Add a short project description for GitHub/LinkedIn
Just tell me!
