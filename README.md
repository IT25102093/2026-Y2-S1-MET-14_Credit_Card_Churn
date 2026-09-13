# IT2011 — AI & Machine Learning: Progress Review I

## Project Title
Predicting Credit Card Customer Churn Using Multi-Quarter Usage Trends

## Dataset Information
- **Dataset:** `BankChurners.csv` (Sakshi Goyal, Kaggle)
- **Size:** 10,127 customer records, 21 columns
- **Domain:** Retail Banking / Retention Analytics
- **Target Variable:** `Attrition_Flag` (Existing Customer: 83.93%, Attrited Customer: 16.07%)

---

## Member Work Distribution

| Student ID | Individual Preprocessing Role | Notebook File |
| :--- | :--- | :--- |
| **IT25102085** | Drop Irrelevant & Leakage Columns | `notebooks/IT25102085_Drop_Leakage_Columns.ipynb` |
| **IT25102086** | Encoding Categorical Variables | `notebooks/IT25102086_Encode_Categorical.ipynb` |
| **IT25102090** | Handling Missing & 'Unknown' Values | `notebooks/IT25102090_Handle_Missing_Values.ipynb` |
| **IT25102091** | Outlier Detection (IQR Method) | `notebooks/IT25102091_Outlier_Detection.ipynb` |
| **IT25102092** | Correlation Analysis (EDA Heatmap) | `notebooks/IT25102092_Correlation_Analysis.ipynb` |
| **IT25102093** | Numerical Feature Scaling (StandardScaler) | `notebooks/IT25102093_Feature_Scaling.ipynb` |

---

## Execution Guide
- `data/raw/`: Contains original `BankChurners.csv`.
- `notebooks/`: Holds individual student notebooks and the integrated `group_pipeline.ipynb`.
- `results/eda_visualizations/`: Visual validation plots for each technique.
- `results/outputs/`: Cleaned and preprocessed splits exported for model training.
- Run `notebooks/group_pipeline.ipynb` to execute the end-to-end data preparation workflow.
