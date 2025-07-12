# 📊 EDA Summary – Loan Default Analysis

## 🔹 Objective:
Explore the dataset to understand relationships between demographic, financial, and behavioral variables and their influence on loan approval status.

---

## 🔹 1. Data Cleaning Summary:
- No missing values found in the dataset.
- All data types verified.
- No duplicates or format issues observed.

---

## 🔹 2. Univariate Analysis:

### Categorical Columns:
- **Gender**: Slightly more male applicants.
- **Education**: Majority are Graduates.
- **Loan Status**: Higher proportion of approvals (`Y`).

### Numerical Columns:
- **Age**: Ranges from 21 to 64; mean ~42 years.
- **Income**: Average ~30,000; min = 5,000, max = ~70,000.
- **Loan Amount**: Average = ~1.18 lakh
- **Credit History**: Binary – 0 or 1 (mostly 1)

---

## 🔹 3. Bivariate Analysis:

### Categorical vs Target (`loan_status`)
- Graduates and Non-Graduates have **similar approval rates**
- Gender shows **no significant difference** in approval

### Numerical vs Target:
- Income and loan_amount show **slightly lower mean values** for rejected loans.
- Boxplots indicate **overlap** between approved and rejected income/loan values.

---

## 🔹 4. Correlation Analysis:
- Correlation heatmap shows **moderate positive** relationship between income and loan amount.
- Credit history has **noticeable impact** on loan approval.

---

## 🔹 5. Outlier Detection:
- Boxplots reveal a few outliers in income and loan amount.
- These were retained as they fall within realistic limits.

---

## 🔹 6. Hypothesis Testing:
- **Chi-square test**: No significant relation between education and loan approval.
- **T-test (Income)**: No significant income difference between approved/rejected loans.
- **T-test (Loan Amount)**: Slightly significant (at 90% confidence).
- **ANOVA (Education vs Income)**: No difference.

---

## ✅ Conclusion:
EDA reveals that:
- Credit history is the **strongest indicator** of loan approval.
- Education and gender have **minimal impact**.
- Numerical features like income/loan_amount have **some mild effect**, but not significant.

