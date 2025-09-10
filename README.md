# Diamond Price Prediction

This repository contains my implementation of a machine learning project that predicts the prices of diamonds based on their attributes. The project demonstrates my experience in data preprocessing, feature engineering, model selection, and evaluation.

---

## Objective
To build regression models that can accurately predict diamond prices, applying industry-standard data science practices while exploring multiple machine learning techniques.

---

## My Experience in This Project
- **Data Analysis & Cleaning**:  
  Explored the Kaggle Diamonds dataset, removed outliers, handled missing values, and ensured numerical and categorical features were properly formatted.

- **Feature Engineering**:  
  Encoded categorical variables (`cut`, `color`, `clarity`) into ordinal or numerical form, created derived features (e.g., volume from x, y, z), and performed scaling when necessary.

- **Exploratory Data Analysis (EDA)**:  
  Visualized distributions, correlations, and relationships between the 4Cs (carat, cut, clarity, color) and price to guide modeling decisions.

- **Model Development**:  
  Trained and compared multiple regression models including:
  - Linear Regression  
  - Ridge / Lasso Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
  - Extra Trees Regressor  
  - XGBoost Regressor  

- **Model Evaluation**:  
  Evaluated models with **R²**, **RMSE**, and **MAE**. Selected the best-performing model based on accuracy and generalization ability.

- **Tools & Workflow**:  
  Worked in Jupyter Notebook, documented process step-by-step, and exported trained models for reuse.

---

## Tools & Libraries Used
- **Python** – programming language  
- **Pandas, NumPy** – data handling and preprocessing  
- **Matplotlib, Seaborn** – data visualization  
- **scikit-learn** – regression models, preprocessing, evaluation metrics  
- **XGBoost** – gradient boosting model  
- **Joblib** – saving and loading trained models  
- **Jupyter Notebook** – interactive development environment

---

## Dataset
- **Source**: Kaggle Diamonds dataset  
- **Features**: carat, cut, color, clarity, depth, table, x, y, z  
- **Target**: price (USD)


