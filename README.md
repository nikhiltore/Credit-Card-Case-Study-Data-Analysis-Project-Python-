**📊 Credit Card Case Study -Data Analysis Project (Python):**
A complete end-to-end analysis of credit card customer behavior, spending patterns, repayments, and profitability using Python, Pandas, Matplotlib, and Seaborn.
This project replicates the PSPD Bank Case Study and delivers a fully solved Jupyter Notebook covering data cleaning, transformations, EDA, visualizations, and business insights.

**📝 Objective**
To analyze credit card customer behavior, spending, repayments, profitability, and segment performance using transactional and customer-level datasets.

**🔍 Key Analysis Performed:**
**✅ 1. Data Quality Fixes**
•	Replaced invalid customer ages (age < 18) with mean age
•	Capped spend > credit limit at 50% of limit
•	Capped repayment > credit limit at limit amount
**✅ 2. Customer & Spend Insights**
•	Count of unique customers
•	Total number of spend categories
•	Average monthly spend per customer
•	Average monthly repayment per customer
•	Monthly profit and bank interest earned
•	Top 5 product types by card issuance
•	City with maximum spend
•	Age groups contributing highest spend
•	Top 10 customers by repayment
**✅ 3. City-wise & Product-wise Analysis**
•	City × Product × Year pivot summary
•	Annual spend split by product and market segment
•	Visual comparison across different regions
**✅ 4. Visualizations & Trends**
•	Monthly spend trends (city-wise)
•	Yearly spend on air tickets category
•	Monthly seasonality by product type
•	Bar charts, line graphs, and facet plots for deep insights
**✅ 5. User-Defined Function**
Created a reusable function to fetch:
Top 10 customers by repayment
Filterable by product type and time period (yearly or monthly).

**📚 Dataset Description:**
Customer Acquisition
•	Customer ID
•	Age
•	City
•	Product Type
•	Credit Limit
Spend
•	Date / Month
•	Customer ID
•	Category
•	Amount
Repayment
•	Date / Month
•	Customer ID
•	Amount

**🛠️ Tech Stack:**
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Jupyter Notebook

**📈 Results & Business Impact:**
•	Identified high-value customer segments
•	Mapped profitability across time periods
•	Detected cities and product categories driving higher revenue
•	Highlighted repayment behavior for risk evaluation
•	Delivered visual analytics for business stakeholders

