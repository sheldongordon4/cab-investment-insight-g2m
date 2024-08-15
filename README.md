# Case Study: G2M Insight for Cab Investment

## Project Overview

XYZ, a private US firm, is exploring investment opportunities in the cab industry. To support their Go-to-Market strategy, an in-depth market analysis has been conducted using data from two prominent cab companies. The objective is to identify which company presents the most promising investment opportunity based on various customer and transaction metrics.

### Data Sources

Four datasets were used for this case study:
- Cab data: "Cab_data.csv" file, containing detailed information about each cab company and their transactions.
- City data: "City.csv" file, containing information about the user bases and cities within which each cab company operates.
- Customer ID data: "customer_ID.csv" file, containing detailed information about each customer and their transactions.
- Transaction ID data: "transaction_ID.csv" file, containing detailed information about each transaction and the associated company.

### Tools
- JupyterLab Notebook

### Data cleaning/preprocessing
- Review and understand field names, data types, and relationships across datasets.
- Merge datasets to create a comprehensive master dataset.
- Rename columns and format data types where necessary.
- Perform feature engineering.

### Exploratory Data Analysis
1. Relationship between trip profit and price charged
2. Number of transactions per company
3. Gross revenue per company
4. Gross profit per company
5. Number of transactions per gender
6. Company profitability per city
7. Gender profitability per city
8. Profitability per year
9. Profitability trend
10. Total number of customers per year per company
11. Customer number trend
12. Number of customers per age group
13. Number of customer per income group
14. Gender profitability per age group
15. Gender profitability per income group

### Results/Findings
- Distance traveled is strongly correlated with trip cost but weakly correlated with trip profit, possibly due to price discounts or issues with the pricing model.
- Yellow Cab outperforms Pink Cab in all 20 cities studied, as well as in transactions, revenue, and profit. Yellow Cab has about 3 times more transactions and is 7.5 times more profitable.
- New York is 8 times more profitable than Los Angeles, the second most profitable city.
- Both companies have stable customer bases, but Yellow Cab has about 3 times more customers.
- There are more male users than female users on both platforms, especially in more profitable cities, with the widest gender gap in New York.
- The 26–35 age group is the most frequent user group, followed by 19–25 and 36–45 age groups. Higher income groups use the services more frequently, true for both genders.
- Profitability per age and income groups mirrors the customer distribution: the 26–35 age group is the most profitable, and higher income groups are more profitable.

### Recommendations
1. Yellow Cab is the superior investment option, outperforming Pink Cab in all metrics and cities studied.
2. Focus Areas:
  - Establish major urban hubs: New York, Los Angeles, Washington DC, Chicago, and Boston, as these are the most profitable.
  - Launch a special campaign for New York, the most profitable city by a significant margin.
3. Target Demographics: Focus on male users, particularly those aged 19-45, and higher income earners.
4. Pricing Review: Review the pricing model to ensure it is optimized and free of issues.
