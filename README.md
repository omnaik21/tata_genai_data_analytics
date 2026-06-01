# 🏦 Tata iQ × Geldium Finance — GenAI Powered Data Analytics

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-1.3-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)
![Forage](https://img.shields.io/badge/Forage-Tata%20iQ-red)

## 📌 Project Overview

An end-to-end AI-powered delinquency prediction and collections 
strategy system built for Geldium Finance as part of the 
**Tata iQ GenAI Powered Data Analytics Job Simulation** on Forage.

As an AI Transformation Consultant, I analysed customer credit card 
data, built a predictive ML model, generated GenAI-powered 
intervention recommendations, and designed a responsible AI 
collections system — delivering all findings to Geldium's 
Head of Collections.

---

## 🗂️ Project Structure
tata_genai_data_analytics/
│
├── data/
│   ├── raw/                  # Original dataset (not tracked)
│   ├── processed/            # Cleaned dataset
│   └── synthetic/            # Synthetic data (if generated)
│
├── notebooks/
│   ├── 01_EDA_risk_profiling.ipynb
│   └── 02_delinquency_prediction_model.ipynb
│
├── reports/
│   ├── figures/              # All saved charts and visualisations
│   ├── EDA_Summary_Report_Geldium_OmNaik.docx
│   ├── Task2_Predictive_Modeling_Plan_OmNaik.docx
│   └── Task3_Collections_Strategy_Report_OmNaik.docx
│
├── resources/                # Reference files and templates
├── src/                      # Utility functions
├── requirements.txt
└── README.md

---

## 📋 Tasks Completed

### ✅ Task 1 — Exploratory Data Analysis & Risk Profiling
- Audited 500-customer financial dataset across 19 features
- Identified and resolved 6 data quality issues
- Discovered 16% delinquency rate — 3× industry average
- Built risk profiling across Employment, Card Type & Location segments
- **Deliverable:** EDA Summary Report (.docx)

### ✅ Task 2 — Predictive Modeling Plan
- Compared Logistic Regression, Random Forest & Gradient Boosting
- Applied SMOTE to correct 5.2:1 class imbalance
- Optimised decision threshold for maximum Recall (1.0)
- Conducted fairness analysis across demographic segments
- **Deliverable:** Predictive Modeling Plan (.docx)

### ✅ Task 3 — GenAI-Powered Stakeholder Recommendations
- Translated ML findings into plain-language executive report
- Built SMART intervention recommendation for Collections team
- Designed P1–P4 risk-tiered outreach framework
- Documented responsible AI ethics and bias mitigation strategy
- **Deliverable:** Collections Strategy Report (.docx)

### ✅ Task 4 — AI System Design & Executive Briefing
- Designed end-to-end agentic AI collections system
- Defined autonomous vs. human-in-the-loop decision boundaries
- Built responsible AI guardrails framework
- Projected $1.9M+ in protected loan balance
- **Deliverable:** Executive PowerPoint (.pptx)

---

## 📊 Key Findings

| Metric | Value |
|---|---|
| Portfolio Delinquency Rate | 16% (3× industry avg) |
| Highest Risk Segment | Business Cards — 21.3% |
| Highest Risk Location | Los Angeles — 19.6% |
| Model Recall | 1.0 (zero delinquents missed) |
| Best Model AUC | 0.41 (Gradient Boosting) |
| Loan Balance at Risk | $1.9M+ |
| Class Imbalance Ratio | 5.2:1 |

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.11 |
| Data Processing | pandas, numpy |
| Visualisation | matplotlib, seaborn |
| Machine Learning | scikit-learn, imbalanced-learn |
| Boosting | GradientBoostingClassifier |
| Imbalance Handling | SMOTE |
| Reporting | python-docx |
| Presentation | pptxgenjs |
| Environment | Jupyter Notebook, VS Code |

---

## ⚙️ Setup & Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/tata-genai-data-analytics.git
cd tata-genai-data-analytics

# Create virtual environment
python3.11 -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows

# Install dependencies
pip install -r requirements.txt
```

---

## 📈 Results Summary

The analysis confirmed that Geldium's delinquency challenge cannot 
be solved by single-metric rules. A Gradient Boosting model with 
SMOTE oversampling successfully identified all delinquent customers 
(Recall=1.0), providing the Collections team with a ranked risk 
score list for targeted outreach — replacing manual, reactive 
case handling with a proactive, data-driven intervention system.

---

## 🔗 Certificate

[Tata iQ GenAI Powered Data Analytics — Forage Certificate](YOUR_CERTIFICATE_LINK)

---

## 👤 Author

**Om Naik** — AI Transformation Consultant  
[LinkedIn](YOUR_LINKEDIN_URL) · [GitHub](YOUR_GITHUB_URL)

---

*This project was completed as part of the Tata iQ Job Simulation 
on Forage. Dataset provided by Forage for educational purposes.*
