# Case Study: G2M Insight for Cab Investment

This case study presents a data-driven market analysis to support the Go-to-Market (G2M) strategy for a private U.S. firm considering investment in the cab industry. Using data from two major cab companies, the goal is to evaluate customer behavior, operational performance, and profitability to determine the most promising investment option.

### Project Overview
The analysis combines four datasets covering cab rides, customer profiles, city demographics, and transactions. By merging and cleaning the data, a master dataset was built to explore transaction-level profitability, customer demographics, and regional performance.

### Data Sources
- 'Cab_data.csv': Company-wise trip data with fare and cost details
- City.csv: Demographic and operational data by city
- customer_ID.csv: Customer-level information
- transaction_ID.csv: Mapping of transactions to companies and customers

🧰 Tools & Techniques
Python
JupyterLab Notebook
Pandas, NumPy, Seaborn, Matplotlib
Data Cleaning & Preprocessing
Feature Engineering
Exploratory Data Analysis (EDA)
🔍 Key EDA Focus Areas
💰 Trip Profit vs. Price Charged
📊 Transactions, Revenue & Profit per Company
🏙️ Profitability by City
👤 Customer Distribution by Gender, Age, and Income
📈 Profitability Trends Over Time
👥 Customer Base Growth by Year and Segment
🧮 Demographic Profitability (by Age, Income, Gender)

<img width="932" alt="Screenshot 2024-08-26 at 10 20 37" src="https://github.com/user-attachments/assets/3db4f0b6-5696-485e-a0e7-e44de179fe38">

📈 Results & Insights
Distance vs. Profit: While trip distance is strongly correlated with cost, it's weakly correlated with profit — possibly due to pricing inconsistencies or discounts.
Yellow Cab Dominance: Yellow Cab is the clear market leader — with 3x the transactions and 7.5x the profit of Pink Cab, and dominance in all 20 cities analyzed.
Regional Trends:
New York is the most profitable city (8× more than Los Angeles).
Other key hubs: Los Angeles, Washington DC, Chicago, Boston
Demographic Trends:
Male users dominate in usage and profitability, especially in top cities.
Most frequent and profitable age group: 26–35, followed by 19–25 and 36–45.
Higher income groups contribute significantly more to revenue.
🧭 Strategic Recommendations
✅ Invest in Yellow Cab, as it outperforms Pink Cab in all key metrics.
🌆 Focus on Urban Hubs: Especially New York, Los Angeles, and other high-profit metros.
🎯 Target Demographics:
Males aged 19–45
High-income earners
💸 Pricing Strategy Review: Investigate weak profit correlation with trip distance to refine pricing structure and boost margins.
