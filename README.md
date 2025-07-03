# 🏦 Power BI Banking Dashboard

An interactive and insightful **Banking Dashboard** designed using **Power BI**, integrated with Python-based data preprocessing and exploratory analysis. This project showcases how financial institutions can derive actionable insights from raw banking data.

---

## 📊 Project Overview

This dashboard is built to help **bankers, analysts, and executives** get a comprehensive view of client behavior, loans, deposits, and risk profiles.

The Power BI report includes:
- **Loan Analysis**
- **Deposit Analysis**
- **Summary Page**
- Dynamic Slicers (Gender, Year, Relationship, Advisor)
- KPI Cards & Visual Segmentation (Income Band, Nationality, Occupation)

---

## 📁 Dataset Structure

The dataset includes over **20+ columns**, covering customer financial profiles:

| Column Name               | Description                                  |
|---------------------------|----------------------------------------------|
| Client ID                | Unique identifier for each client            |
| Name                     | Client name                                  |
| Age                      | Age of the client                            |
| Location ID              | Regional ID                                  |
| Joined Bank              | Year client joined the bank                  |
| Banking Contact          | Type of banking contact                      |
| Nationality              | Country of origin                            |
| Occupation               | Job title                                    |
| Fee Structure            | Fee model assigned to client                 |
| Loyalty Classification   | Loyalty level (Gold, Silver, etc.)           |
| Estimated Income         | Annual income estimate                       |
| Superannuation Savings   | Retirement savings                           |
| Amount of Credit Cards   | No. of credit cards                          |
| Credit Card Balance      | Current credit balance                       |
| Bank Loans               | Total loans held                             |
| Bank Deposits            | Total deposits held                          |
| Checking Accounts        | Funds in checking account                    |
| Saving Accounts          | Funds in savings account                     |
| Foreign Currency Account | Currency held outside local bank             |
| Business Lending         | Loans for business purposes                  |
| Properties Owned         | Number of properties                         |
| Risk Weighting           | Risk score/classification                    |
| BRId                     | Banking Relationship ID                      |
| GenderId                 | Gender ID (for filtering)                    |
| IAId                     | Institution Advisor ID                       |

---

## 🐍 Python Component

Before visualization, the dataset was:
- Cleaned for missing/null values
- Transformed to ensure consistency
- Aggregated for KPIs like loan amount, deposits, and balances

The notebook includes:
- Data Cleaning
- Feature Engineering
- Outlier Handling
- Summary Statistics & Charts (optional)

---

## 📎 Power BI Dashboard Highlights

- 📌 **KPIs**: Total Loans, Deposits, Credit Card Balances, Business Lending
- 🧭 **Filters**: Gender, Year of Joining, Institution Advisor
- 📈 **Visuals**: 
  - Bar charts (Loan/Deposit by Occupation, Nationality)
  - Donut charts (by Income Band)
  - Slicers and clean layout for usability

---

## 🛠 Tools Used

| Tool      | Purpose                         |
|-----------|---------------------------------|
| Power BI  | Dashboard creation & visualization |
| Python (Pandas, NumPy) | Data processing & cleaning |
| Excel/CSV | Data source format              |

---

## 🚀 How to Run

### Power BI:
1. Download the `.pbix` file from this repo
2. Open it in Power BI Desktop
3. Use slicers and filters to interact with the dashboard

### Python:
1. Clone this repo
2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn
3. Run .ipynb for data preprocessing and exploration.


** Author
**Vibhor Singla
Junior Developer (Intern) | Data Enthusiast | Power BI Learner
