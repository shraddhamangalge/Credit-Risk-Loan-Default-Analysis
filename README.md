# 💳 Credit Risk Loan Default Analysis | Exploratory Data Analysis (EDA)

## 📌 Project Overview

Credit risk assessment is an important process in the banking and financial industry. Financial institutions need to understand borrower characteristics and loan-related factors to assess the risk of loan defaults.

This project focuses on performing **Exploratory Data Analysis (EDA)** on a credit risk loan dataset to identify patterns, trends, and relationships between borrower profiles, loan characteristics, and loan default status.

Using Python and its data analysis and visualization libraries, this project explores the factors associated with loan defaults and generates meaningful insights that can support better financial risk assessment.

## 🎯 Project Objectives

- Understand the structure and characteristics of the credit risk dataset.
- Perform data cleaning and preprocessing.
- Identify and handle missing values and duplicate records.
- Analyze borrower demographics and financial characteristics.
- Explore loan distribution across different categories.
- Identify patterns associated with loan defaults.
- Analyze relationships between loan characteristics and default status.
- Perform statistical analysis to examine associations between selected variables.
- Generate meaningful business insights from the analysis.

## 📂 Dataset Information

The dataset contains information about borrowers, their financial backgrounds, and loan details.

### Key Features

| Column Name | Description |
|---|---|
| person_age | Age of the borrower |
| person_income | Annual income of the borrower |
| person_emp_length | Employment length in years |
| person_home_ownership | Home ownership status |
| loan_intent | Purpose of the loan |
| loan_grade | Loan grade assigned to the borrower |
| loan_amnt | Loan amount |
| loan_int_rate | Loan interest rate |
| loan_percent_income | Loan amount as a percentage of income |
| cb_person_default_on_file | Previous default history |
| cb_person_cred_hist_length | Length of credit history |
| loan_status | Loan default status (Target Variable) |

**Target Variable: `loan_status`**

- `0` – No Default
- `1` – Default

## 🛠️ Technologies & Libraries Used

- **Python** – Programming language
- **Jupyter Notebook** – Development environment
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **SciPy** – Statistical analysis and hypothesis testing

## 🔍 Project Workflow

### 1. Data Loading & Understanding
- Imported the required Python libraries.
- Loaded the dataset using Pandas.
- Examined dataset dimensions, columns, and data types.
- Used descriptive statistics to understand numerical variables.

### 2. Data Cleaning & Preprocessing
- Checked for missing values.
- Identified and handled duplicate records.
- Examined invalid and unusual values.
- Applied appropriate missing-value treatment.
- Prepared the dataset for further analysis.

### 3. Univariate Analysis
Analyzed individual variables to understand their distributions and characteristics.

- Distribution of borrower age and income.
- Employment length distribution.
- Loan amount and interest rate distribution.
- Loan purpose and loan grade distribution.
- Borrower home ownership categories.

### 4. Bivariate Analysis
Explored relationships between two variables to identify patterns associated with loan defaults.

- Loan status vs. loan grade.
- Loan status vs. loan intent.
- Loan status vs. home ownership.
- Loan status vs. interest rate.
- Loan status vs. income.
- Loan status vs. loan amount.

### 5. Multivariate Analysis
- Examined relationships among multiple numerical variables.
- Used correlation analysis to understand variable relationships.
- Visualized correlations using heatmaps.
- Explored patterns across different borrower and loan characteristics.

### 6. Statistical Analysis
- Applied statistical techniques to examine relationships between selected categorical variables.
- Used the Chi-Square test to investigate the association between previous default history and current loan status.

### 7. Key Insights & Business Takeaways
Summarized the major patterns observed during the analysis and identified borrower and loan characteristics associated with higher default rates.

## 📊 Key Business Questions

This project explores the following questions:

1. Which age groups have a higher representation in loan applications?
2. How does borrower income vary across different loan categories?
3. Which loan grades have higher default rates?
4. Does loan interest rate vary between default and non-default borrowers?
5. Which loan purposes are associated with higher default rates?
6. How does home ownership relate to loan default status?
7. Is previous default history associated with current loan defaults?
8. What relationships exist between borrower financial characteristics and loan default status?

## 📈 Key Outcomes

- Developed an understanding of borrower financial characteristics and loan distributions.
- Identified patterns in loan default rates across different categories.
- Explored relationships between loan grades, interest rates, income, and default status.
- Examined the association between previous default history and current loan status.
- Generated data-driven observations to understand credit risk patterns.

## 📁 Repository Structure

```text
Credit-Risk-Loan-Default-Analysis/
│
├── Credit_Risk_Loan_Default_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Credit-Risk-Loan-Default-Analysis.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Credit-Risk-Loan-Default-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Add the Dataset

Place the dataset file named `credit_risk_dataset.csv` in the project directory.

### Step 5: Run Jupyter Notebook

```bash
jupyter notebook
```

Open `Credit_Risk_Loan_Default_Analysis.ipynb` and execute the cells sequentially.

## 💡 Conclusion

This project demonstrates the application of Exploratory Data Analysis techniques in the financial domain.

By analyzing borrower information, loan characteristics, and default patterns, the project provides insights into factors associated with credit risk.

The analysis highlights how data cleaning, statistical analysis, and visualization can help transform raw financial data into meaningful information for better understanding of loan default behavior.

## 👩‍💻 Author

**Shraddha Mangalge**

Information Technology Graduate | Data Analytics Enthusiast
