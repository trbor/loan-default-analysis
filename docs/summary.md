# 📘 Project Summary: Loan Default Analysis

## 📌 Objective:
The purpose of this project is to identify key factors that influence whether a loan application gets approved or rejected. By analyzing patterns in demographic, financial, and behavioral data, this project helps understand what drives loan defaults and approvals.

---

## 🛠️ Tools and Libraries Used:
- **Python Libraries**: pandas, numpy, seaborn, matplotlib, scipy
- **Jupyter Notebook** for coding and visualization
- **CSV Dataset** used for data analysis

---

## 🔍 Project Workflow:

1. **Data Cleaning**:
   - Checked for missing values, incorrect formats, and outliers.

2. **Exploratory Data Analysis (EDA)**:
   - Univariate and bivariate visualizations for key variables.
   - Countplots, histograms, boxplots, and correlation heatmaps.

3. **Statistical Testing**:
   - Chi-square test: Categorical vs categorical
   - T-tests: Numerical vs categorical
   - ANOVA: Group-wise mean comparison

4. **Visualization Output**:
   - Saved in the `/output/` folder for report and presentation.

5. **Reporting**:
   - Created `eda_summary.md` to document technical insights.
   - This `summary.md` provides a business-level overview.

---

## 🧠 Key Insights:

- **Credit History** has a major influence on loan approval.
- **Education** and **Gender** have no significant impact on loan status.
- **Income** and **Loan Amount** do not show strong statistical differences between approved and rejected loans.
- The dataset is clean and balanced, suitable for future modeling.

---

## 📈 Project Outcome:
This project forms the base for risk analysis and loan prediction systems. Future versions can integrate machine learning models to automate decision-making and improve accuracy.

---

## ✅ Folder Structure:
loan-default-analysis/
├── data/ # Raw dataset
├── notebooks/ # Jupyter notebooks (EDA & tests)
├── output/ # Saved charts/images
├── docs/ # eda_summary.md and this summary.md
├── README.md # Project homepage
├── requirements.txt # Dependencies

---

## 🏁 Status:
✅ Completed EDA + Statistical Tests  
🔜 Next Phase: Predictive Modeling (ML)
