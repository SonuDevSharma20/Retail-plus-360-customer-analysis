# Retail-plus-360-customer-analysis
Retail Transaction Data Analysis
Project Overview :-
This project performs a comprehensive data analysis on a retail dataset containing 100,000 transaction records. The objective is to clean raw transaction data, perform exploratory analysis to understand customer behavior, and prepare a final dataset for reporting.

Analysis Workflow :-
The analysis follows a structured process as documented in the Pythonfile.ipynb notebook:

1. Environment 'Setup' :-
Libraries: Utilizes pandas, numpy, matplotlib, and seaborn for data manipulation and visualization.

Data Loading: Imports raw data from retailpulse_data.csv.

2. Data Inspection :-
Dataset Shape: Confirms the volume of data (100,000 rows and 13 columns).

Content Preview: Inspects initial records and column structures to identify key features like product_category, total_amount, and customer_segment.

3. Exploratory Data Analysis (EDA) :-
Statistical Summaries: Generates descriptive statistics for numerical fields.

Customer Insights: Analyzes demographics (age ranging from 18 to 70) and spending patterns.

4. Data Cleaning & Export :-
Categorization: Organizes data by city, product category, and payment method.

Final Output: Exports the processed and refined information into cleaned_dataset.csv for further reporting.

Conclusion & Results :-
The analysis highlights several key insights from the retail operations:

Scalability: Successfully handled a large-scale dataset of 100,000 transactions across 15 different cities.

Diverse Customer Base: Identified clear segments—Budget, Regular, and Premium—spanning a wide age demographic.

Operational Readiness: The automated cleaning process ensures that raw transaction logs are converted into a reliable format for business intelligence tools.
