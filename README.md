Customer Churn Analysis & Customer Intelligence

📊 Project Overview

This project analyzes customer churn and subscription behavior to identify factors associated with customer attrition, revenue exposure and customer-service issues.

The analysis was performed using **Python, SQL/SQLite and Jupyter Notebook**, with statistical analysis and visualizations created using **Pandas, NumPy, Matplotlib and Seaborn**.

🎯 Business Objective

The primary objective was to understand:

* Overall customer churn and retention
* Churn across different subscription plans
* Geographic differences in churn
* Average revenue generated per customer
* Customer tenure
* Revenue exposed to churn
* Customer complaints and escalations
* Relationship between escalations and customer churn

🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQL
* SQLite
* Jupyter Notebook

🔍 Analysis Performed

1. Data Exploration

Analyzed customer and subscription attributes including:

* Customer ID
* Subscription starts date
* Subscription type
* Renewal date
* Plan type
* Contract type
* Cancellation date
* Cancellation reason
* Monthly charges
* CLTV
* Churn score
* Churn flag
* Country and state
* Gender
* Complaint date
* Escalations
* CSAT score
* Complaint count

2. SQL / SQLite Analysis

Connected Python to a SQLite database and inspected the available customer and subscription tables before loading the data into Pandas for further analysis.

3. Exploratory Data Analysis

Performed customer churn analysis using:

* Group-by analysis
* Aggregations
* Correlation analysis
* Churn segmentation
* Plan-level analysis
* State-level analysis
* Correlation heatmap
* Pair plot
* Bar charts

4. Customer Churn KPIs

Calculated the following business KPIs:

| KPI                             |    Result |
| ------------------------------- | ----------|
| Overall Churn Rate              |     28.57%|
| Retention Rate                  |     71.43%|
| Basic Plan Churn                |     60.00%|
| Standard Plan Churn             |     22.22%|
| Premium Plan Churn              |     14.29%|
| ARPU                            |      18.85|
| Average Customer Tenure         | 1,524 days|
| Revenue at Risk                 |     73.94K|
| Escalation Rate                 |     19.05%|
| Average Complaints per Customer |       0.43 
| Escalation vs Churn Correlation |       0.77|

💡 Key Insights

* The overall customer churn rate was **28.57%**, resulting in a retention rate of **71.43%**.
* The **Basic plan** showed the highest churn rate at **60%**, substantially higher than Standard and Premium plans.
* **Premium customers had the lowest churn rate at 14.29%**, while Standard customers recorded 22.22%.
* Approximately **73.94K** in monthly revenue was identified as being at risk from churned customers.
* The analysis found a **0.77 correlation between escalations and churn**, indicating a strong positive relationship in this dataset.
* The analysis also measured customer complaints, with an average of **0.43 complaints per customer**.

📈 Visualizations

The project includes visual analysis of:

* Churn Rate by Plan Type
* Churn Rate by State
* Correlation Heatmap
* Pairwise Relationships
* Customer Churn Metrics


🚀 Skills Demonstrated

**Data Analysis:** Exploratory Data Analysis, KPI Development, Customer Segmentation, Business Analysis

**Python:** Pandas, NumPy, Matplotlib, Seaborn

**SQL:** SQLite, SQL querying, table inspection, data extraction

**Business Intelligence:** Churn Analysis, Retention Analysis, Revenue-at-Risk Analysis, Customer Intelligence

**Analytics:** Correlation Analysis, Data Visualization, Metric Development
