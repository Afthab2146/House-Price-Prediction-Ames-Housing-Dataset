[ames_housing_no_missing.csv](https://github.com/user-attachments/files/21813529/ames_housing_no_missing.csv)# House-Price-Prediction-Ames-Housing-Dataset
This project focuses on predicting house prices using the Ames Housing dataset. It demonstrates an end-to-end Machine Learning workflow including preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.
The primary goal is to compare different regression techniques (Linear, Ridge, Lasso, and Polynomial Regression) and analyze their performance on real-world housing data

**Workflow**
1)Data Loading
*Dataset:https://github.com/Afthab2146/House-Price-Prediction-Ames-Housing-Dataset/blob/main/ames_housing_no_missing.csv
*Target variable: SalePrice

2)Data Preprocessing
*Separated numeric and categorical features
*Applied:
  *StandardScaler for numeric features
  *OneHotEncoder for categorical features
  *Used ColumnTransformer + Pipeline for automation

3)Modeling
*Linear Regression (baseline)
*Ridge Regression (L2 regularization)
*Lasso Regression (L1 regularization)
*Polynomial Regression (degree = 2)

4)Hyperparameter Tuning
*Used GridSearchCV for tuning α (regularization strength) in Ridge and Lasso

5)Evaluation Metrics
*R² Score (goodness of fit)
*Mean Squared Error (MSE)

6)Visualization & Diagnostics
*Actual vs Predicted Scatter Plot
*Residual Distribution (with KDE)



