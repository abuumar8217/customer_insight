# SuperStore Customer Insights Analysis

This repository contains a detailed exploratory data analysis (EDA) and regression modeling project based on a retail dataset (`SuperStore-Data.csv`). The objective is to understand customer purchasing behavior through visual analytics and statistical modeling.

---

## 📊 Key Features

- Descriptive statistics and visualizations of income and purchase patterns.
- Outlier detection and handling (IQR method).
- Imputation of missing values.
- Derived metrics:
  - Total amount spent on various product categories.
  - Total number of purchases across channels.
  - Total children per household.
- Multiple comparative visualizations:
  - By education, marital status, complaints, number of children, etc.
- Linear and multivariate regression models to analyze:
  - Impact of income and demographic variables on total spending.
  - Relationship between recency, income, and purchases.

---

## 📁 Files Included

- `superstore_analysis.ipynb` – Main analysis notebook.
- `SuperStore-Data.csv` – Input dataset.
- `README.md` – Overview and documentation.

---

## 🛠️ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels

You can install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn statsmodels
