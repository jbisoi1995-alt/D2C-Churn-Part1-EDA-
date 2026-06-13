Data Quality Report
Dataset Overview
The analysis included the following datasets:
●	customers.csv
●	orders.csv
●	support_tickets.csv
●	web_events_snapshot.csv
●	churn_labels.csv
●	intervention_history.csv
●	rfm_modeling_snapshot.csv
Missing Values
customers.csv
●	loyalty_tier: 1,386 missing values
●	skin_type: 401 missing values
orders.csv
●	rating: 80 missing values
Other datasets
No significant missing values detected.
Duplicate Records
No duplicate records were identified in any dataset.
Outlier Analysis
Outliers were observed in:
●	recency_days
●	monetary_180d
●	frequency_180d
These observations likely represent genuine customer behavior and were retained for analysis.
Join Key Validation
Customer IDs were successfully used as primary keys across datasets.
No major join inconsistencies were detected.
Date Consistency
Date fields were reviewed and found to be logically consistent.
No future dates or invalid temporal sequences were observed.
Potential Data Leakage
The following fields require caution during predictive modeling:
●	churn_next_60d (target variable)
●	split column
●	campaign intervention variables occurring after the prediction date
These variables should not be used incorrectly when training churn prediction models.
Recommendations
1.	Impute missing loyalty_tier values.
2.	Handle missing ratings appropriately.
3.	Monitor customer behavior outliers separately.
4.	Maintain customer_id integrity across systems.
5.	Validate future campaign data before model development.

