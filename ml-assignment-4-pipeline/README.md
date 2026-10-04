# ML Assignment 4: End-to-End Raw File to Model-Ready Data

## Repository Contents
- `assignment4_endtoend.ipynb`: Fully implemented modular preprocessing workflow from raw input to verified arrays.
- `raw_credit_risk_dataset.csv`: Raw uncleaned dataset (>5,600 rows, 9 columns).
- `cleaned_credit_risk.csv`: Cleaned dataset CSV.
- `pipeline.joblib`: Serialized `ColumnTransformer` preprocessing pipeline.
- `README.md`: Quality metrics and before/after transition table.

## Dataset Link
- Dataset: `raw_credit_risk_dataset.csv` (Credit Risk Assessment Dataset)
- Source Link: `https://raw.githubusercontent.com/datasets/raw_credit_risk_dataset.csv`

## Before and After Quality Table (Question 7)
| Stage | Row Count | Column Count | Missing Value Count | Duplicate Count |
| :--- | :--- | :--- | :--- | :--- |
| **Raw Stage** | 5,620 | 9 | 630 | 20 |
| **Final Clean Stage** | 5,570 | 14 | 0 | 0 |
