# Customer-Churn-Analysis-with-Machine-Learning
📌 Project Overview

This project demonstrates an end-to-end data analytics pipeline for predicting and analyzing telecom customer churn using SQL, Python, and Power BI. The solution integrates data engineering, machine learning, and business intelligence to deliver actionable insights that help reduce customer attrition and improve retention strategies.

🚀 Key Features

SQL (Data Engineering):

Performed data extraction, exploration, and cleaning on 6,000+ customer records.

Built ETL workflows with staging and production tables.

Created business-ready SQL views to feed into Python models and Power BI dashboards.

Python (Machine Learning):

Trained a Random Forest Classifier achieving 84% accuracy.

Conducted feature engineering & importance analysis to identify key churn drivers (contract type, monthly charges, support services).

Automated churn prediction for new customers and exported churn-risk reports in CSV format.

Power BI (Business Intelligence):

Designed interactive dashboards tracking churn KPIs by gender, age, contract, state, and payment method.

Revealed key insights:

Overall churn rate: 27%

High churn among monthly contract customers & fiber optic users

380 high-risk customers identified for targeted retention campaigns

🛠️ Tech Stack & Skills Used

SQL Server (T-SQL, Views, ETL, Data Modeling)

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Machine Learning (Random Forest, Predictive Modeling, Feature Engineering)

Power BI (DAX, Power Query, Data Visualization, Business Intelligence)

Excel (Exploratory Analysis, Data Validation)

📊 Business Impact

✔️ Enabled data-driven decision making for customer success and marketing teams.
✔️ Delivered actionable insights on churn risk segmentation to reduce attrition.
✔️ Built a scalable pipeline for continuous churn prediction and BI reporting.

📂 Repository Structure
├── SQL/                  # Data exploration, cleaning, ETL scripts
├── Python/               # Churn prediction model (Random Forest)
├── PowerBI/              # Dashboard files and visuals
├── Data/                 # Sample datasets (anonymized)
├── Outputs/              # Model outputs, reports, and CSV exports
└── README.md             # Project documentation

📈 Results

Model Accuracy: 84%

Non-churn Recall: 93%

Churn F1-score: 70%

Business Insights: Identified 380 high-risk customers for targeted campaigns

🔗 How to Use

SQL: Run the ETL scripts to prepare staging and production tables.

Python: Train and evaluate the model using churn_model.py.

Power BI: Connect to SQL views or exported CSVs to refresh dashboards.
