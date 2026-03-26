 # 🏦 FinTrust Bank — Loan Portfolio & Credit Risk Analytics

![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)

## 📌 Project Overview

End-to-end financial analytics project analyzing **51,336 real 
Indian bank loan accounts** using CIBIL bureau data for credit 
risk assessment and portfolio performance reporting.

## 🎯 Business Problem

FinTrust Bank needs to:
- Identify high-risk borrowers before they become NPAs
- Classify loan portfolio by risk tiers (P1/P2/P3/P4)
- Build an interactive dashboard for the credit risk committee
- Meet RBI compliance reporting requirements

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Excel | Data cleaning, pivot analysis, portfolio summary |
| MySQL | SQL queries, risk segmentation, NPA analysis |
| Power BI | Interactive 4-page credit risk dashboard |

## 📊 Dataset

- **Source:** Real Indian Bank Internal Data + CIBIL Bureau
- **Records:** 51,336 customer loan accounts
- **Tables:** 2 (Internal Bank Data + External CIBIL Data)
- **Key Fields:** Credit Score, DPD, Loan Types, Income, Demographics

## 🔍 Key Finance Terms

| Term | Meaning |
|------|---------|
| CIBIL | India's credit bureau — financial report card |
| DPD | Days Past Due — how late a payment is |
| NPA | Non Performing Asset — loan overdue 90+ days |
| P1-P4 | Risk tiers — P1 best, P4 highest risk |
| LTV | Loan to Value ratio |

## 📈 Key Findings

### Portfolio Overview
- **Total Customers:** 51,336
- **Average CIBIL Score:** 680 (below 700 benchmark ⚠️)
- **High Risk (P4) Customers:** 5,882 (11.5%)
- **Average Monthly Income:** Rs.26,424

### Critical Insights
1. 📊 P2 tier dominates at 62.7% — healthy core portfolio
2. 🚨 Average CIBIL score 680 — below RBI benchmark of 700
3. 💡 P4 customers earn MORE than P2 (Rs.27,370 vs Rs.25,887)
   — income alone is NOT a reliable risk predictor
4. ⚠️ 4,848 P4 customers show zero DPD currently
   — future NPA pipeline risk
5. 🔍 Customer ID 5262 — 21 years old with 235 loan accounts
   — potential fraud flag requiring investigation
6. 📚 Graduate customers show HIGHEST risk at 13%
   — education level not a reliable risk predictor

### Loan Portfolio
- Gold loans dominate at 76% penetration
- Home loan customers have highest credit scores (693)
- Personal loans carry highest unsecured risk

## 📁 Project Structure
```
FinTrust-Bank-Loan-Analytics/
├── data/
│   ├── raw/          → Original dataset files
│   └── cleaned/      → Cleaned data
├── excel/            → Excel analysis workbook
├── sql/              → 6 SQL analytical scripts
├── powerbi/          → Power BI dashboard (.pbix)
├── outputs/
│   └── screenshots/  → Dashboard screenshots
└── README.md
```

## 🗄️ SQL Scripts

| Script | Description |
|--------|-------------|
| 01_portfolio_summary | Overall portfolio KPIs |
| 02_risk_tier_analysis | P1-P4 tier deep dive |
| 03_credit_risk_analysis | DPD bucket analysis |
| 04_loan_type_analysis | Gold, Home, PL breakdown |
| 05_customer_profile | Education, gender, income |
| 06_top_risk_customers | Top 20 critical accounts |

## 📊 Dashboard Preview

### Page 1 — Executive Summary
![Executive Summary](outputs/screenshots/page1_executive_summary.png)

### Page 2 — Credit Risk Analysis
![Credit Risk](outputs/screenshots/page2_credit_risk.png)

### Page 3 — Loan Portfolio Analysis
![Loan Analysis](outputs/screenshots/page3_loan_analysis.png)

### Page 4 — Customer Profile
![Customer Profile](outputs/screenshots/page4_customer_profile.png)

## 💡 Business Recommendations

1. **Immediate Action** — Review 551 customers with 11+ DPD
2. **Fraud Investigation** — Audit accounts with 100+ loan accounts
3. **Risk Strategy** — Stop using income as primary risk indicator
4. **Portfolio Health** — Improve avg CIBIL score from 680 to 700+
5. **NPA Prevention** — Monitor 4,848 P4 customers with 0 DPD

## 👤 Author

**Vivek Kumar**
Finance Analyst | Data Analytics Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](your-linkedin-url)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](your-github-url)
```

---

**Step 6 —** Scroll down → Commit message:
```
Add professional README with key findings
