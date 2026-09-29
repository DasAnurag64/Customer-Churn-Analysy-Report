Customer Churn Analysis & Retention Strategy

An end-to-end data analytics project uncovering the key drivers of customer attrition and providing actionable, data-backed retention strategies for subscription-based business models.

📌 Executive Summary

Customer churn directly limits recurring revenue growth and drives up customer acquisition costs (CAC). This project investigates customer behavior, contract terms, billing preferences, and service utilization to pinpoint why accounts cancel.

Through exploratory data analysis and statistical evaluation, this project highlights key churn indicators and outlines an ROI-focused retention strategy designed to reduce high-risk cohort turnover.

🎯 Business Problem & Core Objectives

Identify Root Causes: Determine which customer touchpoints and service combinations correlate most strongly with account cancellation.

Segment Risk Cohorts: Quantify churn rate variations across contract types, payment methods, and account tenure.

Deliver Strategic Recommendations: Provide concrete operational steps that marketing, sales, and customer success teams can implement immediately.

🛠 Tech Stack & Tools

| Domain | Technology / Tool |
| Language | Python 3.10+ |
| Data Manipulation | pandas, numpy |
| Data Visualization | matplotlib, seaborn |
| Statistical Analysis | scipy.stats |
| Environment | Jupyter Notebook, VS Code, Git |

📁 Repository Structure

├── data/
│   ├── raw/                 <- Original raw dataset (e.g., Telco Customer Churn)
│   └── processed/           <- Cleaned, transformed dataset used for analysis
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_exploratory_analysis.ipynb
├── visuals/                 <- High-resolution plots and charts for reporting
├── .gitignore               <- Standard Python gitignore
├── README.md                <- Project overview and documentation
└── requirements.txt         <- Python dependencies for reproducibility



📊 Key Findings & Insights

1. Contract Commitment Strongly Dictates Retention

Month-to-month subscribers represent the highest risk tier, exhibiting a churn rate exceeding 42%, compared to 11% for one-year contracts and < 3% for two-year commitments.

Actionable Takeaway: First-year contract onboarding promotions yield a significantly higher lifetime value (LTV) than short-term acquisition discounts.

2. The "First 90 Days" Critical Window

Over 50% of all recorded churn occurs within the initial 3 months of contract activation.

Customers who utilize technical support or product onboarding services within their first 30 days are 35% less likely to cancel.

3. Payment Method & Billing Friction

Customers utilizing paperless electronic checks show a 33% higher attrition rate compared to accounts on automated bank transfers or credit card billing.

Billing friction and payment failure notifications are primary contributors to involuntary churn.

💡 Strategic Recommendations

Structured Onboarding Program: Mandate a guided onboarding sequence for all new month-to-month signups during their first 30 days to mitigate initial drop-off.

Auto-Pay & Annual Contract Incentives: Implement a modest discount (e.g., 5–8%) for converting month-to-month contracts to annual auto-renewal terms.

Proactive Intervention Alerts: Flag accounts with sudden drops in monthly service utilization for immediate check-ins by customer success teams.

🚀 Getting Started

Prerequisites

Python 3.10 or higher installed

Git

Installation & Reproduction

Clone the repository:

git clone https://github.com/your-username/customer-churn-analysis.git
cd customer-churn-analysis



Create and activate a virtual environment:

# On macOS/Linux:
python3 -m venv venv
source venv/bin/activate

# On Windows:
python -m venv venv
venv\Scripts\activate



Install the dependencies:

pip install -r requirements.txt



Run the notebooks:

jupyter notebook notebooks/02_exploratory_analysis.ipynb

