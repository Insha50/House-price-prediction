# 🏠 House Price Prediction Using Random Forest

## 📌 Problem Statement
Predict house prices using features like size, location, and condition.

## 📂 Dataset Source
- Dataset: `kc_house_data.csv`
- Source: [Kaggle – King County House Sales](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

## 🔧 Workflow Overview
1. **Data Cleaning**: Removed irrelevant columns and handled missing values.
2. **EDA**: Correlation heatmap and price distribution.
3. **Modeling**: Compared Random Forest and Linear Regression.
4. **Outlier Removal**: Used IQR method to clean data.
5. **Improved Model**: Tuned Random Forest for better accuracy.
6. **Unseen Data Testing**: Simulated new samples and predicted prices.

## 📊 Key Results
| Model Stage         | R² Score | MAE (₹) | RMSE (₹) |
|---------------------|----------|---------|----------|
| Before Cleaning     | 0.821    | 81,505  | 164,415  |
| After Cleaning      | 0.855    | 53,269  | 77,642   |

## 📈 Visuals
- Correlation heatmap
- Price distribution histogram
- Actual vs predicted scatter plot
- Unseen data prediction histogram

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

