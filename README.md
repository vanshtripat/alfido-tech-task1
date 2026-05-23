# Alfido Tech Internship — Task 1: Customer Behavior Analysis

## Project Overview
Analysis of 250,000 e-commerce transactions to identify customer segments, purchase patterns, and churn risks.

**Dataset:** [Kaggle – Customer Behavior Analysis](https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis)  
**Author:** Vansh | B.Tech CS, Sharda University  
**Date:** May 2026

---

## Repository Structure
```
alfido-tech-task1/
├── customer_behavior_analysis.ipynb   # Main analysis notebook
├── reports/
│   └── customer_behavior_report.pdf   # Executive summary report
├── assets/
│   ├── chart1_bar.png
│   ├── chart2_line.png
│   └── chart3_pie.png
└── README.md
```

> **Large asset (18MB Excel dataset)** is hosted on Google Drive:  
> 📁 [ecommerce_customer_data_custom_ratios.xlsx – Google Drive](https://drive.google.com/YOUR_LINK_HERE)

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total transactions | 250,000 |
| Unique customers | 50,000 |
| Date range | Jan 2020 – Sep 2023 |
| Churn rate | **19.9%** |
| Return rate | 49.8% |
| Avg monthly revenue | ~INR 15M |

## 3 Actionable Insights for Alfido Tech

1. **Churn intervention** – 60-day inactivity trigger + personalised re-engagement email
2. **Fix Returns data gap** – 47,596 missing values (19%) hide half the return behaviour
3. **Diversify payment mix** – 2–3% cashback on PayPal/Crypto to cut credit card fees

---

## How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/alfido-tech-task1.git
cd alfido-tech-task1

# Install dependencies
pip install pandas matplotlib openpyxl nbformat

# Download the dataset from Google Drive (link above) and place it in root
# Then run the notebook
jupyter notebook customer_behavior_analysis.ipynb
```

---

## Report
The full executive PDF report is in `reports/customer_behavior_report.pdf`  
and also available on [Google Drive](https://drive.google.com/YOUR_LINK_HERE).
