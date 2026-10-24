# Customer Churn Analysis

An end-to-end analysis of customer churn: exploring why customers leave, identifying the key factors behind churn, and presenting the findings in an interactive Power BI dashboard.

> **Note:** Items in `[square brackets]` are placeholders. Fill them in with details from your dataset and results.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Repository Structure](#repository-structure)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
- [Key Insights](#key-insights)
- [Dashboard Preview](#dashboard-preview)
- [Getting Started](#getting-started)
- [Recommendations](#recommendations)
- [Future Work](#future-work)
- [Author](#author)

---

## Project Overview

Customer churn, when customers stop doing business with a company, directly hurts revenue and growth. Retaining an existing customer is usually cheaper than acquiring a new one, so understanding *who* churns and *why* is valuable.

This project:

- Cleans and prepares customer data for analysis
- Performs exploratory data analysis (EDA) to uncover churn patterns
- Identifies the key drivers of churn
- Visualizes results in an interactive Power BI dashboard
- Summarizes actionable recommendations to reduce churn

## Business Problem

- What percentage of customers are churning?
- Which customer segments (demographics, contract type, services, tenure, etc.) are most at risk?
- Which factors are most strongly associated with churn?
- What can the business do to retain customers?

## Dataset

- **Source:** [add dataset source / link, e.g. Kaggle, company data]
- **Size:** [number of rows] customers × [number of columns] features
- **Target variable:** `Churn` (Yes/No)
- **Feature categories:** [e.g. customer demographics, account information, subscribed services, billing and payment details]

The raw data is stored in the [`Data/`](Data) folder.

## Repository Structure

```
Customer-Churn-Analysis/
├── Data/              # Raw and/or cleaned datasets
├── Images/            # Charts, screenshots, and dashboard previews
├── Notebooks/         # Jupyter notebooks for cleaning, EDA, and modeling
├── PowerBI/           # Power BI dashboard file (.pbix)
├── Requirements/      # Python dependencies
├── .gitignore
└── README.md
```

## Tools & Technologies

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn [add/remove as applicable, e.g. Scikit-learn]
- **Visualization / BI:** Power BI
- **Environment:** Jupyter Notebook

## Methodology

1. **Data Cleaning**: handle missing values, fix data types, remove duplicates, and standardize columns.
2. **Exploratory Data Analysis**: analyze churn rate overall and across segments such as contract type, tenure, payment method, and services.
3. **Feature Analysis**: identify the variables most associated with churn.
4. **[Optional] Predictive Modeling**: build and evaluate a churn prediction model (e.g. Logistic Regression, Random Forest). Report metrics such as accuracy, precision, recall, and ROC-AUC.
5. **Dashboard Development**: build an interactive Power BI report with KPIs, filters, and visual breakdowns.
6. **Recommendations**: translate findings into retention strategies.

## Key Insights

> Replace these with your actual findings.

- Overall churn rate: **[X%]**
- Customers with **[e.g. month-to-month contracts]** show the highest churn
- Churn is highest among customers with **[e.g. low tenure]**
- **[Another insight, e.g. higher monthly charges correlate with higher churn]**
- **[Another insight about a service, payment method, or segment]**

## Dashboard Preview

Add screenshots from the `Images/` folder, for example:

```markdown
![Dashboard Overview](Images/dashboard_overview.png)
```

The Power BI file is available in the [`PowerBI/`](PowerBI) folder. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Power BI Desktop (to view the dashboard)

### Installation

```bash
# Clone the repository
git clone https://github.com/muskangarg1735-max/Customer-Churn-Analysis.git
cd Customer-Churn-Analysis

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r Requirements/requirements.txt
```

> Adjust the requirements file name/path if it differs.

### Running the Project

```bash
jupyter notebook
```

Open the notebook(s) in the `Notebooks/` folder and run the cells in order.

## Recommendations

> Tailor these to your findings.

- Offer incentives for customers to move from short-term to longer-term contracts
- Create onboarding and engagement programs for new customers, who are the most likely to leave
- Review pricing and bundles for high-risk, high-charge segments
- Proactively reach out to at-risk customers using the identified churn indicators

## Future Work

- Deploy the churn prediction model as an app or API
- Add customer lifetime value (CLV) analysis
- Experiment with additional models and hyperparameter tuning
- Automate data refresh for the Power BI dashboard

## Author

**Muskan Garg**
GitHub: [@muskangarg1735-max](https://github.com/muskangarg1735-max)

---

If you found this project useful, consider giving it a ⭐
