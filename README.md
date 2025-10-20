# Banking Domain Data Analysis Using Python, Sql & Power BI.
##  Project Overview
This project focuses on analyzing and visualizing banking data to gain actionable insights into customer behavior, product usage, and financial performance.  
The workflow integrates **Python for data cleaning and EDA**, **SQL for data transformation**, and **Power BI for interactive dashboard visualization**.

---

##  Objective
The main objective of this project is to uncover meaningful insights from banking customer data and to support strategic business decisions.  
Key goals include:
- Understanding relationships between different account types and customer behavior.  
- Monitoring customer churn, deposits, loan performance and risks.  
- Designing an interactive dashboard to visualize financial trends.  
- Enabling data-driven decision-making across banking operations.

---
## Dataset Used
[Dataset Link](https://github.com/Maher12-hub/Banking-Domain-Data-Analysis-Project-With-Python-Sql-And-Power-BI/blob/70cb64ccdee1140942dd3d24e716e123a40de5c6/Banking.xlsx)

---

##  Key Performance Indicators (KPIs)
The dashboard and analysis focus on the following KPIs:

1. **Total Customers** – Total count of active customers.  
2. **Customer Risk Rate** – Percentage of high risk cutomers.  
3. **Average Account Balance** – Mean customer balance across different account types.    
4. **Average Credit Score** – Measure of financial health of customers.  
5. **Total Bank Deposits** – Aggregated deposits across all account types.
6. **Total Bank Loans** – Aggregated loans across all account types.
7. **Bank loans by category** – Bank loans by banking relations, nationality, income band and occupations.
8. **Bank deposits by category** – Bank deposits by banking relations, nationality, income band and occupations.    


---

##  Business Questions Answered
- Which customer segments contribute the most to total deposits?    
- How do credit scores and income levels affect loan approvals?  
- What are the correlations between different types of accounts (checking, savings, foreign currency)?  
- Which regions or customer types show the highest profitability?
- Which occupation types or employment categories contribute the most to total deposits?
- What is the total deposit volume across different account types (checking, savings, fixed deposits, etc.)?
- What are the average deposits per customer segment (e.g. Nationality, gender, income, Occupation)?

---

##  Process Workflow

### 1. **Exploratory Data Analysis (Python)**
- Imported and cleaned raw data using pandas and numpy.  
- Handled missing values and standardized column formats.  
- Used matplotlib and seaborn for visualizing distributions and correlations.  
- Key finding:  
  > Strong positive correlation observed among **Bank Deposits**, **Checking Accounts**, **Savings Accounts**, and **Foreign Currency Accounts**, indicating that customers with high balances in one account type often maintain substantial funds across others as well.

### 2. **Data Transformation (SQL)**
- Loaded the cleaned dataset into a SQL database.  
- Created SQL views and aggregations for Power BI import.  
- Applied filters, grouping, and joins to compute KPIs (e.g., churn, deposits by region, customer segments).

### 3. **Data Visualization (Power BI)**
- Connected Power BI to the SQL database.  
- Built multiple pages for different insights:  
  - **Financial Metrics Dashboard** – Deposits, balances, and loan performance.  
  - **Customer Segmentation Dashboard** – Behavior across income levels, Nationality, Occupation, and credit scores.  
- Added interactive filters for region, gender, Joining year and Banking relations.

---
## Dashboard Image
![image alt](https://github.com/Maher12-hub/Banking-Domain-Data-Analysis-Project-With-Python-Sql-And-Power-BI/blob/a1849f40d175e1a1d1e5b724fd337d7f2daaad9a/Banking%20Dashboard%20Screenshots.png)

##  Key Insights
- Customers maintaining **multiple account types** show higher loyalty and overall deposit value.  
- Income and credit score strongly influence loan approval likelihood.  
- Low-income and single-product customers are more prone to churn.  
- Middle-aged customers (25–40) contribute the most to total deposits and product adoption.
- Male customers slightly outnumber females, but female customers maintain higher average account balances and are less likely to churn.
- Customers maintaining multiple account types (e.g., checking + savings + fixed deposit) show 30–40% higher total balances on average.
- Foreign Currency Accounts show strong correlation with high-income and high-credit-score customers — a premium segment worth targeted campaigns.
- Churned customers typically have lower income, fewer products, and shorter tenure with the bank.
- There’s a positive correlation between credit score, income level, and loan approval rate.  
- Regional variation suggests targeted marketing can improve product penetration.
  
---

##  Conclusion
This project provided a 360° view of banking performance by integrating Python-based data preparation, SQL-based data modeling, and Power BI dashboards.  
The insights can support:
- **Customer retention strategies** (targeting at-risk segments).  
- **Product development** (bundling high-performing account types).  
- **Operational efficiency** through KPI monitoring.
---

##  Tech Stack
- **Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn), SQL  
- **Visualization:** Power BI  
- **Tools:** Jupyter Notebook, DAX, Power Query  

---
