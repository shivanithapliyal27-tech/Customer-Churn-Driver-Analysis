# Customer Churn Driver Analysis

## Project Overview
This project analyzes customer churn in the IBM Telco Customer Churn dataset using Python and Power BI. The goal is to understand customer behavior, compare churn across customer segments, and identify areas where retention strategies may be useful.

## Objectives
- Measure customer churn and retention.
- Explore churn patterns across contract types, tenure, internet services, payment methods, and support services.
- Clean and prepare data for analysis.
- Build a Power BI dashboard with key performance indicators and churn-rate comparisons.
- Provide data-driven customer retention recommendations.

## Tools and Technologies
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Microsoft Power BI

## Dataset
The project uses the IBM Telco Customer Churn dataset, which contains 7,043 customer records and customer/service attributes such as tenure, contract type, internet service, payment method, monthly charges, total charges, and churn status.


## Project Workflow
1. Load the dataset into Google Colab.
2. Inspect columns, data types, missing values, and duplicate records.
3. Convert `TotalCharges` to a numeric field and review blank values.
4. Perform exploratory data analysis to examine churn distribution.
5. Compare churn rates across relevant customer segments.
6. Export cleaned data, churn-driver comparisons, and KPI summaries.
7. Build an interactive Power BI dashboard to present the findings.

## Key Metrics
For the standard IBM Telco Customer Churn dataset:

- **Total Customers:** 7,043
- **Churned Customers:** 1,869
- **Retained Customers:** 5,174
- **Overall Churn Rate:** Approximately 26.54%


## Key Analysis Areas
- Churn rate by contract type
- Churn rate by customer tenure group
- Churn rate by internet service
- Churn rate by payment method
- Churn patterns related to technical support and online security services

The analysis identifies associations in the dataset; it does not prove that any single feature causes churn.

## Business Recommendations
- Provide proactive onboarding and support for customers in their early tenure.
- Review month-to-month customer segments and test appropriate retention offers.
- Make technical support and online security options easier to understand and access.
- Investigate billing and payment issues in segments with elevated churn.
- Track churn KPIs regularly and test retention initiatives before scaling them.

## Project Files
- `README.md` — Project overview and instructions
- `Customer_Churn_Driver_Analysis_Project_Report.docx` — Detailed project report
- `Churn_Driver_Analysis.ipynb` — Python notebook from Google Colab
- `Churn_Driver_Analysis.pbix` — Power BI dashboard
- `Telco_Churn_Cleaned.csv` — Cleaned dataset
- `Churn_Driver_Ranking.csv` — Churn-rate comparisons by feature and category
- `Churn_Project_KPIs.csv` — Summary metrics

*Upload only files that you have created, and update filenames if yours are different.*

## Limitations
- This is descriptive analysis, so relationships should not be interpreted as proven causes.
- The dataset is a snapshot and may not capture changes in customer behavior over time.
- Recommendations should be validated with additional data or controlled experiments.

## Conclusion
This project demonstrates a complete data analytics workflow, from data cleaning and exploratory analysis in Python to interactive dashboard development in Power BI. The findings help highlight customer segments that may benefit from targeted retention strategies.


