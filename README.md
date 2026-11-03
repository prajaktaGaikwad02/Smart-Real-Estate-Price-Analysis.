#  Personal Financial Data Analysis & Budget Performance Dashboard

**End-to-End Data Analytics Project using Python**

#  Project Overview

- This project focuses on analyzing personal financial transactions and budget data to understand income patterns, spending behavior, savings, and budget performance.
- It demonstrates an end-to-end Data Analytics workflow, including data loading, data cleaning, missing value treatment, exploratory data analysis (EDA), data visualization, and financial insight generation using Python.
- The project uses real-world transaction and budget datasets to identify major spending categories, monitor monthly expenses, and compare actual expenses against planned budgets.

#  Project Objectives

- Load and analyze personal financial transaction and budget datasets.
- Clean and preprocess raw financial data.
- Handle missing values appropriately.
- Perform Exploratory Data Analysis (EDA).
- Analyze income and expense patterns.
- Monitor monthly expense trends.
- Compare actual expenses with budget allocations.
- Generate actionable financial insights.
- Support better budgeting and financial decision-making.

#  Skills & Tools Used (ATS Optimized)

- Python
- NumPy
- Pandas
- Data Cleaning & Preprocessing
- Missing Value Treatment
- Exploratory Data Analysis (EDA)
- Financial Data Analysis
- Income & Expense Analysis
- Budget Analysis
- Variance Analysis
- KPI Analysis
- Data Visualization
- Matplotlib
- Business Analytics

#  Dataset Information

**Dataset Names:**
1. Personal Transactions Dataset (`personal_transactions.csv`)
2. Budget Dataset (`Budget.csv`)

**Personal Transactions Dataset:**
- Rows: 806
- Columns: 6

**Key Features:**
- Date – Transaction date
- Description – Transaction details
- Amount – Transaction amount
- Transaction Type – Debit and Credit
- Category – Transaction category
- Account Name – Account associated with the transaction

**Budget Dataset:**
- Contains budget allocation information.
- Columns: Category, Budget

**Key Features:**
- Category – Expense category
- Budget – Allocated budget amount

#  Project Workflow

## 1️. Data Loading & Understanding

- Loaded datasets using Pandas.
- Checked dataset shape, column names, and data types.
- Reviewed statistical summaries.
- Identified missing values and duplicate records.

## 2️. Data Cleaning & Preprocessing

- Validated column names and data types.
- Converted the Date column into datetime format.
- Standardized transaction type values.
- Checked numerical and categorical columns.
- Prepared datasets for further analysis.

## 3️. Missing Value Treatment

**Method Used:**

- Identified missing values in both datasets.
- Applied numerical mean imputation where appropriate.
- Validated the datasets after missing value treatment.

## 4️. Exploratory Data Analysis (EDA)

**EDA was performed using:**

1. Histograms
2. Bar charts
3. Line charts
4. Category-wise aggregation
5. Budget comparison charts

**Key Analysis Areas:**

1. Distribution of transaction amounts.
2. Expenses by category.
3. Income vs expenses analysis.
4. Monthly expense trends.
5. Budget allocation by category.
6. Actual expenses vs budget comparison.
7. Relationship between income and expenses.

## 5️. Financial Performance Analysis

- Calculated total income using credit transactions.
- Calculated total expenses using debit transactions.
- Compared income and expenses.
- Evaluated the difference between budget allocation and actual expenses.
- Identified major spending categories.

## 6️. Budget vs Actual Analysis

- Compared actual expenses against allocated budgets.
- Identified categories exceeding their budget.
- Highlighted categories with remaining budget.
- Evaluated spending patterns to support better financial planning.

## 7️. Data Visualization Dashboard

- Created financial visualizations using:
  - Matplotlib
  - Pandas
- Presented income, expenses, and monthly spending trends.
- Visualized category-wise expenses and budget allocation.
- Compared budgeted amounts with actual expenses.
- Developed visual insights to make financial information easier to understand.

#  Key Insights

1. Identified major expense categories and spending patterns.
2. Analyzed the relationship between income and expenses.
3. Evaluated monthly expense fluctuations.
4. Identified categories with the highest budget allocation.
5. Compared actual expenses against planned budgets.
6. Highlighted opportunities for expense control and improved savings.

#  Business Recommendations

1. Monitor high-spending categories to control unnecessary expenses.
2. Compare actual expenses with allocated budgets regularly.
3. Review monthly spending trends to improve financial planning.
4. Maintain a balance between income and expenses.
5. Allocate budgets based on historical spending patterns.
6. Identify opportunities to increase savings and improve financial stability.

#  Limitations & Assumptions

**Limitations:**

- Budget dataset contains category-wise allocations without date information.
- Budget comparisons are based on total category-level expenses.
- No predictive modeling or future expense forecasting included.
- Financial insights depend on the accuracy and completeness of transaction records.

**Assumptions:**

- Credit transactions are treated as incoming amounts.
- Debit transactions are treated as expenses.
- Budget allocations represent planned spending limits.
- Transaction amounts are assumed to be recorded accurately.

#  Final Conclusion

This project successfully transformed raw personal financial transaction and budget data into structured, meaningful, and insight-driven analytics.

By applying Python-based data cleaning, exploratory data analysis, financial calculations, and visualization techniques, the project provides insights into income, expenses, spending behavior, and budget performance.

The analysis supports better financial planning, expense monitoring, budget control, and informed financial decision-making.
