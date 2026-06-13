Customer Churn Analysis – Part 1
Project Objective
This project performs data auditing, exploratory data analysis (EDA), and business understanding for a Direct-to-Consumer (D2C) customer churn dataset.
The goal is to identify customer behavior patterns, assess data quality, and generate business hypotheses related to churn risk.
Repository Contents
●	eda_audit.ipynb
●	data_quality_report.md
●	business_memo.md
●	requirements.txt
●	Visualizations/
Data Audit Activities
●	Missing value analysis
●	Duplicate record analysis
●	Outlier inspection
●	Join key validation
●	Date consistency checks
●	Leakage assessment
Exploratory Analysis
The analysis covers:
●	Customer demographics
●	Loyalty behavior
●	Acquisition channels
●	Purchase frequency
●	Monetary value
●	Product engagement
●	Churn distribution
Key Churn Risk Hypotheses
1.	High recency increases churn probability.
2.	Low purchase frequency increases churn risk.
3.	Lower customer spending is associated with churn.
4.	Silver-tier customers are more likely to churn.
5.	Lower website engagement increases churn probability.
Tools Used
●	Python
●	Pandas
●	NumPy
●	Matplotlib
●	Seaborn
How to Run
Install dependencies:
pip install -r requirements.txt
Open:
eda_audit.ipynb
and run all cells.

