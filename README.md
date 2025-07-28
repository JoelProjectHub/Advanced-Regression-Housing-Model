# 🏠 Advanced Regression Housing Model

A machine learning project focused on predicting housing prices using advanced regression techniques, extensive feature engineering, and hyperparameter tuning. Built as an end-to-end pipeline with emphasis on feature manipulation and model optimization.

## ✨ Features
- 🛠️ **Extensive Feature Engineering**:
  - Derived features like total square footage, total baths, porch area, quality scores, and ratios (e.g., living area vs. lot size)
  - Automated feature generation (interaction terms, log/square transformations)
- 🔍 **Data Preprocessing**:
  - Handling missing values with imputation
  - Standardization and encoding of numerical and categorical variables
- 🤖 **Modeling**:
  - Linear Regression, Ridge, Lasso
  - Random Forest, Gradient Boosting, XGBoost
  - Stacking Regressors
- ⚡ **Hyperparameter Optimization**:
  - Optuna for automated XGBoost tuning
  - GridSearchCV / RandomizedSearchCV for other models
- 📊 **Evaluation Metrics**:
  - RMSLE (Root Mean Squared Log Error)
  - R², MAE, MSE

## 🛠️ Tech Stack
- **Python**: pandas, numpy, seaborn, matplotlib
- **ML Frameworks**: scikit-learn, XGBoost
- **Optimization**: Optuna
- **Visualization**: SHAP values, feature importance, correlation heatmaps
