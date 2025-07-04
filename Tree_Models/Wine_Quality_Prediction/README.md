# 🍷 Wine Quality Prediction using Random Forest

This notebook predicts wine quality scores based on physicochemical properties using the Random Forest algorithm.

## 📌 Objective
To build a regression model that estimates wine quality from its chemical features.

## 🗂️ Dataset
- **File**: [Assumed loaded or use from UCI]  
- Columns include: `alcohol`, `sulphates`, `citric acid`, `density`, etc.

## 🛠️ Tools & Libraries
- Python, Pandas, Seaborn, Matplotlib
- scikit-learn (RandomForestRegressor, metrics)

## 📈 Workflow
1. Import and analyze the dataset
2. Train/test split
3. Fit Random Forest model
4. Evaluate using MAE, RMSE, and R² Score

## ✅ Results
- Random Forest handled non-linearity and interactions well
- Important features: `alcohol`, `volatile acidity`, `density`

## 📎 How to Run
- Open the notebook
- Run all cells (dataset is likely included or loaded inline)

## 📚 Future Work
- Compare with Decision Tree, XGBoost, or Gradient Boosting
- Tune hyperparameters using GridSearchCV
