# TP2 - Machine Learning  
## Life Expectancy Prediction with Random Forest

### 🎯 Objective

The goal of this exercise is to predict **life expectancy** based on various **health, economic, and social indicators** using a **Random Forest Regressor**. This work is part of **TP2 in the Machine Learning course**.

### 📊 Dataset Description

The dataset used, `Life Expectancy Data.csv`, contains global data including:
- **Target variable**: `Life expectancy`
- **Features**: indicators like GDP, alcohol consumption, schooling, BMI, etc.
- **Categorical columns**: `Country`, `Status` (Developed/Developing)

Dataset source: [Kaggle](https://www.kaggle.com/) 

### 🛠️ Workflow

1. **Data Cleaning**
   - Removal of missing values (`dropna`)
   - Label encoding for categorical feature `Status`

2. **Feature Engineering**
   - Exclusion of `Country` (non-numerical, too specific)
   - Target: `Life expectancy`

3. **Model Training**
   - Train/Test split (80/20)
   - Training with `RandomForestRegressor` from `scikit-learn`

4. **Evaluation**
   - Metrics: RMSE, R² Score
   - Feature importance analysis and visualization with seaborn

5. **Visualization**
   - Top 10 most important features influencing life expectancy


### 🧰 Technologies

- Python 3
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
