# 💰 Codealpha_task1

**TASK 3: Data Visualization – Loan Default Dataset (Finance Domain)**

This repository presents a comprehensive data visualization project using a public Loan Default dataset. It was created as part of an internship task to uncover patterns in loan approvals and rejections, and to deliver actionable insights through visual analysis.

---

## 🎯 TASK Objectives

- Transform raw loan data into visual formats like charts and graphs
- Use Matplotlib and Seaborn to create professional visualizations
- Reveal financial trends and insights clearly
- Craft a compelling data story to support loan decision-making
- Build a strong portfolio project with impactful visual design

---

## 🔍 Key Questions Explored

1. What credit features influence loan approvals?
2. How do LTV, DTI, and credit scores affect loan decisions?
3. Which regions and age groups have higher approval rates?
4. What’s the impact of gender or application type?
5. Are financial features correlated?

---

## 📂 Data Summary

- **File**: `loan_default.csv`
- **Columns**:
  - Categorical: Gender, Region, Credit Worthiness, Submission Type, Loan Purpose, etc.
  - Numerical: Credit Score, LTV (Loan to Value), DTI Ratio, Age
- **Cleaning**:
  - Missing values dropped
  - Data preprocessed and ready for visualization
  - No encoding required for graphs

---

## 📊 Visualizations Created

- Countplot – Loan status by gender, region, and submission type
- Histplot – Credit score distribution
- Violin/Box Plot – LTV and DTI by loan status
- Heatmap – Correlation between credit-related features
- Age and region-based visual trends

---

## 📚 Data Story: What Drives Loan Approval?

### Insight 1: Credit Factors Drive Approval

- Higher credit scores and lower LTV/DTI ratios increase approval chance  
- 📌 *Action:* Lenders can automate thresholds for safer lending

### Insight 2: Regional and Age-Based Trends

- South region and 35–44 age group are the most active and approved
- 📌 *Action:* Focus outreach or financial services in these segments

### Insight 3: Submission Method Matters

- Applications marked as “pre-approved” and “to_inst” are more successful  
- 📌 *Action:* Streamline submission methods for applicants

---

## 📋 Summary of Decisions You Can Support

- Credit scoring risk thresholds
- Applicant segmentation by age/region
- Approval policy improvement based on past trends
- Early rejection prediction using DTI/LTV

---

## 📁 Project Structure

LoanDefault_DataViz/
├── dataset/
│ └── loan_default.csv
├── graphs/
│ ├── loan_status.png
│ ├── gender_vs_status.png
│ ├── credit_score_distribution.png
│ ├── ltv_by_loan_status.png
│ ├── dti_by_status.png
│ ├── submission_vs_status.png
│ ├── loan_status_by_region.png
│ └── correlation_heatmap.png
├── notebooks/
│ └── LoanDefault_Visualization.ipynb
├── README.md
└── requirements.txt


---

## 🛠️ Tools Used

- Python
- Pandas – Data cleaning
- Matplotlib – Visual styling
- Seaborn – Statistical visualizations
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
