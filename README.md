Medical Insurance Cost Prediction

📌 Overview

This project predicts medical insurance charges using demographic and lifestyle factors such as age, BMI, smoking status, region, and number of dependents. Multiple regression models were built and compared to identify the best-performing approach.

🔧 Preprocessing

Exploratory Data Analysis (EDA)

One-hot encoding for categorical variables

Pipelines and ColumnTransformer to prevent data leakage

Log transformation of target for linear and SVR models

Feature scaling applied where required

🤖 Models Used

Linear Regression (baseline)

Ridge Regression

Support Vector Regression (SVR)

Decision Tree Regressor

Random Forest Regressor

XGBoost Regressor

📈 Evaluation

Models were evaluated using R², RMSE, and Actual vs Predicted plots, with cross-validation and hyperparameter tuning applied to improve generalization.

🏆 Best Model

XGBoost Regressor achieved the best performance, showing strong generalization, low error, and effective handling of non-linear relationships.

📌 Key Insight

Smoking status is the most influential factor in predicting insurance costs.

🛠 Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
