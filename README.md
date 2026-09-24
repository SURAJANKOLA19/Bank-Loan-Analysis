# 📊 Bank Loan Analytics Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)
![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-blue)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

This project presents an **interactive Bank Loan Analytics Dashboard built using Microsoft Power BI**.

The dashboard analyzes loan application and loan performance data to provide insights into **loan applications, funded amounts, repayments, borrower characteristics, loan quality, and overall portfolio performance**.

The project demonstrates an end-to-end data analytics workflow, including:

* Data cleaning and transformation
* Data modeling
* KPI development
* DAX calculations
* Interactive Power BI dashboards
* Trend analysis
* Loan portfolio analysis
* Business-focused insights

---

## 🎯 Business Objective

The primary objective of this project is to help a financial institution understand its loan portfolio and monitor key performance indicators.

The dashboard helps answer questions such as:

* How many loan applications were received?
* How much money was funded?
* How much has been received as repayment?
* What is the average interest rate?
* What percentage of loans are considered good or bad?
* Which loan purposes generate the highest funding?
* How does loan performance change over time?
* Which borrower segments have higher loan activity?
* How are loans distributed across different categories?

---

# 📈 Key KPIs

The dashboard tracks several important financial and operational metrics.

### Loan Application Metrics

* **Total Loan Applications**
* **Month-to-Date Loan Applications**
* **Previous Month Loan Applications**
* **Month-over-Month Growth**

### Financial Metrics

* **Total Funded Amount**
* **Total Amount Received**
* **Average Interest Rate**
* **Average Debt-to-Income Ratio**

### Loan Quality Metrics

* **Good Loan Applications**
* **Bad Loan Applications**
* **Good Loan Percentage**
* **Bad Loan Percentage**

These KPIs provide a high-level view of the overall health and performance of the loan portfolio.

---

# 📊 Dashboard Pages

## 1. Summary Dashboard

The summary dashboard provides an executive-level overview of the loan portfolio.

### Key Visualizations

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* Average Interest Rate
* Average DTI
* Good Loan vs Bad Loan
* Monthly Loan Application Trends
* Loan Status Distribution
* Loan Purpose Analysis

### Purpose

This page is designed to give stakeholders a quick understanding of overall loan performance.

---

## 2. Overview Dashboard

The overview page provides deeper analysis of loan activity and trends.

It includes visualizations for:

* Monthly loan applications
* Monthly funded amount
* Monthly amount received
* Loan purpose
* Employee/borrower characteristics
* Loan term
* Home ownership
* Loan grade
* Loan status

The interactive filters allow users to drill down into different segments of the portfolio.

---

## 3. Details Dashboard

The details page provides a more granular view of individual loan records.

Users can analyze loan-level information such as:

* Loan ID
* Loan amount
* Funded amount
* Amount received
* Interest rate
* Loan grade
* Loan purpose
* Loan term
* Employment information
* Home ownership
* Loan status

This page can be used for detailed investigation and validation of the aggregated metrics presented in the dashboard.

---

# 🛠️ Tools & Technologies

| Tool                   | Purpose                                   |
| ---------------------- | ----------------------------------------- |
| **Microsoft Power BI** | Dashboard development and visualization   |
| **Power Query**        | Data cleaning and transformation          |
| **DAX**                | KPI and calculated measure creation       |
| **Data Modeling**      | Structuring analytical data               |
| **Excel / CSV**        | Source data                               |
| **GitHub**             | Project documentation and version control |

---

# 🔄 Data Analytics Workflow

The project follows an end-to-end analytics workflow:

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Business Insights
```

---

# 🧹 Data Preparation

The dataset was prepared using **Power Query**.

The transformation process included:

* Removing unnecessary columns
* Handling missing values
* Checking data types
* Standardizing categorical fields
* Creating calculated columns where required
* Formatting date fields
* Preparing data for analysis
* Validating numerical fields

---

# 🧮 DAX & Calculations

Several DAX measures were created to calculate the major business KPIs.

Examples include:

```DAX
Total Loan Applications =
COUNTROWS(LoanData)
```

```DAX
Total Funded Amount =
SUM(LoanData[funded_amount])
```

```DAX
Total Amount Received =
SUM(LoanData[total_payment])
```

```DAX
Average Interest Rate =
AVERAGE(LoanData[int_rate])
```

```DAX
Average DTI =
AVERAGE(LoanData[dti])
```

Additional measures were created for:

* Good loan percentage
* Bad loan percentage
* Month-to-date metrics
* Previous month comparison
* Month-over-month changes
* Loan status analysis

---

# 📊 Key Analysis Areas

## Loan Performance

The dashboard analyzes the relationship between:

* Loan applications
* Funded amount
* Amount received
* Loan status

This provides an overview of the financial performance of the loan portfolio.

## Loan Quality

Loans are categorized into **Good Loans** and **Bad Loans** based on their status.

This allows the portfolio to be analyzed from a risk and performance perspective.

## Loan Purpose

Loan applications are analyzed across different purposes such as:

* Debt consolidation
* Credit card
* Home improvement
* Major purchase
* Small business
* Other purposes

This helps identify which purposes contribute most to the loan portfolio.

## Borrower Analysis

The dashboard also provides insights into borrower characteristics including:

* Employment length
* Home ownership
* Loan grade
* Loan term
* Debt-to-income ratio

---

# 📷 Dashboard Preview

Add screenshots of your Power BI dashboard here.

Example:

```markdown
![Bank Loan Summary Dashboard](images/dashboard-summary.png)

![Bank Loan Overview Dashboard](images/dashboard-overview.png)

![Bank Loan Details Dashboard](images/dashboard-details.png)
```

Recommended GitHub structure:

```text
Bank-Loan-Analytics-PowerBI/
│
├── README.md
│
├── dataset/
│   └── bank_loan_data.csv
│
├── powerbi/
│   └── Bank_Loan_Analytics.pbix
│
├── screenshots/
│   ├── dashboard-summary.png
│   ├── dashboard-overview.png
│   └── dashboard-details.png
│
└── documentation/
    └── project-notes.md
```

---

# 💡 Business Insights

The dashboard can be used to identify patterns such as:

* Changes in loan application volume over time
* Growth or decline in funded amounts
* Differences between loan purposes
* Distribution of loans across grades
* Good vs bad loan proportions
* Relationship between borrower characteristics and loan performance
* Monthly changes in portfolio activity

> **Note:** Specific numerical insights should be added based on the actual results in the Power BI dashboard.

---

# 🚀 How to Use the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Bank-Loan-Analytics-PowerBI.git
```

### 2. Download/prepare the dataset

Place the dataset inside the `dataset/` folder.

### 3. Open the Power BI file

Open:

```text
powerbi/Bank_Loan_Analytics.pbix
```

using **Microsoft Power BI Desktop**.

### 4. Refresh the data

If the dataset path has changed, update the data source in Power BI and refresh the model.

### 5. Explore the dashboard

Use the filters and interactive visuals to analyze different segments of the loan portfolio.

---

# 🎓 What I Learned

Through this project, I strengthened my understanding of:

* Power BI dashboard development
* Power Query
* Data cleaning
* Data modeling
* DAX
* KPI creation
* Time-based analysis
* Financial data analysis
* Interactive data visualization
* Business-oriented storytelling

---

# 🔗 Project Reference

This project was created as a learning exercise based on the following tutorial:

**YouTube Tutorial:**
https://youtu.be/M_hizoJzKM0

The project was independently implemented for learning and portfolio development purposes.

---

# 👨‍💻 Author

**Suraj Ankola**

Data Analyst | Power BI | SQL | Python | AWS

📌 Interested in Data Analytics, Business Intelligence, Cloud & Data Engineering.

---

## ⭐ If you found this project useful

Feel free to ⭐ star the repository and connect with me on GitHub.

---

### 📄 License

This project is intended for **educational and portfolio purposes**.
