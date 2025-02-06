# Bank-Customer-Churn
This project focuses on analyzing customer churn for a bank using machine learning models. The analysis includes data cleaning, feature engineering, model building, and interpretability techniques. Various models were tested, including Logistic Regression and XGBoost, with additional exploration of feature importance using SHAP and LIME.

## Table of Contents
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Results & Insights](#results-&-insights)
- [Future Improvements](#future-improvements)

## Folder Structure

- **Data/**: Contains the raw data file `Bank_Churn.csv`
- **Notebooks/**: Contains Jupyter notebooks for data exploration, cleaning, and analysis.
  - `Bank Data - Cleaning and Exploratory Analisis`: Data Preparation (cleaning, encoding, feature engineering, outlier detection, normality checks) 
  - `Bank Data - Model 01`: Logistic Regression Model. Trains a baseline logistic regression model. Evaluates performance using classification metrics
  - `Bank Data - Model 02`: XGBoost Model. Implements an XGBoost model to improve performance. Compares results with logistic regression
  - `Bank Data - Model 02 Check`: Feature Importance Analysis. Uses SHAP and LIME for interpretability. Analyzes feature contributions to model predictions
  - `Bank Data - Model 03`: Enhanced Models with New Features. Tests additional feature engineering strategies. Evaluates improvements in model performance

## Technologies Used

- Python
- Pandas, NumPy (Data Processing)
- Scikit-Learn (Machine Learning)
- XGBoost
- SHAP, LIME (Model Interpretability)
- Matplotlib, Seaborn (Visualization)

## Results & Insights

- Logistic Regression provided an initial benchmark but lacked predictive power.
- XGBoost significantly improved performance.
- SHAP and LIME helped understand key factors influencing churn.
- Additional feature engineering further enhanced model accuracy.

## Future Improvements

- Experiment with other models (Random Forest, Neural Networks).
- Fine-tune hyperparameters for better results.
- Incorporate external data for more predictive power.
