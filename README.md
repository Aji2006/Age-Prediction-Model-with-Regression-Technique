# **Age Prediction Model with Regression Technique**
This repository contains the implementation of an age prediction model using regression techniques. The project involves the following steps:
  1. **Exploratory Data Analysis (EDA):**
      Initial analysis and visualization of the dataset to uncover patterns, detect outliers, and prepare the data for modeling.
  2. **Model Training :**
     Various regression models were trained using the following methods:
     - Random Forest Regressor: Configured with n_estimators=100, max_depth=10, max_features=5, max_leaf_nodes=5, and max_samples=3.
     - XGBoost Regressor: Configured with n_estimators=100 and max_depth=10
     - Logistic Regression: Configured with max_iter=100 and solver='newton-cg'.
     - LightGBM Regressor: A gradient-boosting framework optimized for performance and efficiency.
  3. **Hyperparameter Tuning :**
     The performance of XGBoost and Random Forest models was further optimized using:
     - Random Search CV: To explore a wide range of hyperparameter combinations randomly.
     - Bayes Search CV: To efficiently search the hyperparameter space using Bayesian optimization.

## **Setup and Usage**

### **Clone the Repository**
To clone this repository to your local machine, run the following command:
```bash
git clone https://github.com/your-username/age-prediction-regression.git
cd age-prediction-regression
