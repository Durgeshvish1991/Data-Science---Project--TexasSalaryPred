# Texas Employee Salary Prediction

## Problem Statement
Predict Texas state employee salaries based on job and department attributes, and analyze compensation trends to support payroll and workforce-planning decisions.

## Dataset
- Source: Texas state employee salary data (public/Kaggle) — [add your dataset link here]
- 149,000+ rows
- Features include job title, department, hire date, and other employment attributes
- Target variable: annual salary

## Approach
1. Cleaned and processed a large dataset (149,000+ rows), handling missing values and inconsistent categories.
2. Performed EDA to understand salary distribution across departments and job roles.
3. Engineered features to improve model input quality.
4. Trained and compared four regression models: Linear, Lasso, Ridge, and XGBoost.
5. XGBoost delivered the best performance — R² ≈ 0.90, RMSE ≈ 661.

## Key Insights
- XGBoost handled non-linear relationships between job attributes and salary much better than linear models.
- Clear wage disparities were visible across departments, useful for identifying pay-equity gaps.
- Model output can guide payroll benchmarking and departmental budget planning.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib/Seaborn

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
