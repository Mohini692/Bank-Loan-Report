# 📊 Bank Loan Analysis Dashboard (SQL + Power BI)

📌 Project Objective

The objective of this project is to analyze bank loan data to understand loan applications, funding distribution, repayment performance, and risk levels.

The project demonstrates how SQL can be used for data analysis and KPI calculation, and Power BI can be used to build interactive dashboards for business decision-making.

⚙️ Project Workflow

1️⃣ Raw loan dataset imported from CSV file

2️⃣ Data loaded into SQL database

3️⃣ SQL queries used to calculate KPIs and perform analysis

4️⃣ Processed data connected to Power BI for dashboard visualization

🛠 Tools & Technologies

- SQL – Data querying and KPI calculations
- Power BI – Interactive dashboard development
- Excel / CSV – Dataset source
- DAX – Measures and calculations in Power BI

📊 Dashboard Features

1️⃣ Summary Dashboard
- Provides high-level performance metrics.
Key KPIs:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)
- Additional analysis:
- Good Loan vs Bad Loan distribution
- Loan status breakdown
- Month-to-Date (MTD) metrics

2️⃣ Overview Dashboard
#### Provides deeper insights into loan trends.
#### Visualizations include:
- 📈 Loan Applications by Month
- 🗺 Loan Applications by State
- ⏳ Loan Term Distribution (36 vs 60 months)
- 👨‍💼 Loan Applications by Employment Length
- 🎯 Loan Applications by Purpose
- 🏠 Loan Distribution by Home Ownership

3️⃣ Detailed Dashboard
Displays loan-level information including:
- Loan ID
- Purpose
- Home Ownership
- Loan Grade & Sub Grade
- Issue Date
- Funded Amount
- Interest Rate
- Installment
- mount Received

Includes filters for:
* State
* Grade
* Loan Quality (Good vs Bad)

🧮 SQL Analysis

SQL queries were used to calculate key metrics such as:
- Total Loan Applications
- Month-to-Date Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI
- Good Loan Percentage
- Bad Loan Percentage

Additional queries analyze loan distribution by:
- State
- Loan Purpose
- Loan Term
- Employment Length
- Home Ownership

📈 Key Business Insights

✔ 86.2% loans are Good Loans
Most borrowers successfully repay loans.

✔ Debt Consolidation is the most common loan purpose

✔ Renters apply for more loans than homeowners

✔ Borrowers with 10+ years of employment apply for the most loans

✔ 36-month loans are more popular than 60-month loans
