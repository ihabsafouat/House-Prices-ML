# 🏠 House Prices - Advanced Regression Techniques

This project predicts house sale prices using advanced regression techniques. The dataset comes from the [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## 📊 Project Overview

- Perform detailed EDA
- Handle missing values and skewed features
- Apply feature transformations
- Train multiple regression models
- Optimize and ensemble models for better performance

## 📁 Dataset

- `train.csv`: Contains 79 explanatory variables describing houses in Ames, Iowa and the target variable `SalePrice`
- `test.csv`: Similar structure as training set but missing `SalePrice`

## 🔧 Technologies Used

- Python (3.8+)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost, LightGBM
- Jupyter Notebook

## 🔍 Exploratory Data Analysis

- Visualized target distribution and log-transformed `SalePrice`
- Detected outliers and handled them accordingly
- Checked correlations with heatmaps and scatterplots
- Analyzed missing data patterns

## 🛠️ Data Preprocessing

- Log-transform of skewed numeric features
- Label encoding of categorical variables
- One-hot encoding for nominal features
- Imputed missing values with domain-informed strategies
- Standardized numeric features

## 🤖 Models Used

- Linear Regression
- Ridge and Lasso Regression
- XGBoost Regressor
- LightGBM Regressor
- Stacking and Ensembling

## 📈 Evaluation

Used Root Mean Squared Log Error (RMSLE) on the validation set.

| Model         | RMSLE   |
|---------------|---------|
| Lasso         | 0.12    |
| XGBoost       | 0.11    |
| LightGBM      | 0.109   |
| Ensemble      | 0.108   |

## 📝 Submission

- Generated predictions on `test.csv`
- Created a `submission.csv` in the required Kaggle format

## 🧠 Learnings

- Techniques to clean and engineer complex real-world datasets
- Regularization (L1, L2) and its impact on overfitting
- Ensembling models for improved accuracy
- Use of log-transformations to reduce skew and normalize distributions

## 🚀 How to Run

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run Jupyter Notebook: `jupyter notebook House_Prices_Prediction.ipynb`

## 📎 Resources

- [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- [Hands-On ML Book](https://github.com/ageron/handson-ml2)
- [Scikit-learn Docs](https://scikit-learn.org/)

---

