📊 Retail Demand Analysis

📌 Overview
This project analyses retail sales data to evaluate whether key commercial factors such as pricing, promotions, seasonality, and product category influence customer demand.
The objective is to test common business assumptions and identify the true drivers of sales performance.

📂 Dataset
The dataset contains over 70,000 transactions, including:
Units Sold
Inventory Level
Price
Discount
Competitor Pricing
Demand Forecast
Seasonality
Product Category
Holiday/Promotion indicators

🧹 Data Preparation
The dataset was first cleaned and validated through:
Checking for missing values
Verifying data types
Removing inconsistencies
Filtering incomplete time periods (e.g. final month anomalies)

📈 Analysis Performed
The analysis focused on evaluating the relationship between demand (Units Sold) and key variables:
Pricing vs Demand
Promotions and Discounts
Seasonality trends
Time-based analysis (monthly sales)
Category-level performance
Correlation analysis across all variables

🔍 Key Findings
Pricing showed no significant correlation with demand
Promotions and discounts had negligible impact on sales
Seasonality effects were minimal across all periods
Demand remained stable over time
Product categories showed only minor variation in sales

⚠️ Limitations
The dataset appears to have weak relationships between variables
Key behavioural drivers (e.g. customer preferences, brand effects) are not included
Results may reflect synthetic or simplified data structure

🧠 Conclusion
The analysis suggests that demand in this dataset is largely independent of traditional commercial levers such as pricing and promotions.
This highlights the importance of:
Validating assumptions with data
Recognising when datasets lack explanatory power
Identifying missing variables in analytical models

🚀 Next Steps
Explore more complex or real-world datasets
Introduce predictive modelling techniques
Incorporate additional variables to better explain demand behaviour

🛠️ Tools Used
Python
Pandas
Matplotlib / Seaborn
Jupyter Notebook
