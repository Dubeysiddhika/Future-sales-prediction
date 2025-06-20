🛒 Future Sales Prediction Model – BigMart Dataset
This project predicts future sales using the BigMart Sales dataset from Kaggle. It utilizes machine learning techniques (XGBoost) to model the relationship between item/store attributes and their sales, with the goal of forecasting sales for the next 3 months.

🔍 Problem Statement
Retail chains like BigMart need accurate sales forecasting for inventory and supply chain optimization. This model learns patterns from historical sales data to predict future sales values at the item and outlet level.

📂 Dataset
Source: BigMart Sales Dataset on Kaggle

Files used: Train.csv (for model training)

Features include:

Item type, weight, MRP

Outlet type, size, location

Historical sales

🧠 Model
XGBoost Regressor: Chosen for its performance and robustness in tabular data.

Handles missing values and label encodes categorical features.

Trained on 80% of data, validated on 20%.

🔮 Output
Predicts sales values for the next 3 months by sampling from trained feature space.

Visualization of predicted vs actual sales.

Output shown in console (optionally exportable to CSV/Excel).

📊 Libraries Used
pandas, scikit-learn, xgboost, matplotlib
