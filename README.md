# Flight-Delay-Prediction-XGBoost-Balanced-Decision-Tress
Predicting flight delays before they happen using historical airline data and modern ML techniques.
🚀 Overview
This project tackles a real-world classification problem: predicting whether a flight will be delayed by 60+ minutes.
Using a mix of exploratory analysis, feature engineering, and tree-based ensemble models, it delivers interpretable and high-performance predictions.
🧩 Approach
Data Wrangling
Converted Date → extracted month & day
Encoded categorical columns (Airline, Origin, Dest)
Created binary target is_delayed_60+
Modeling
Balanced Random Forest → handled class imbalance
XGBoost (tuned with GridSearchCV) → optimized for ROC-AUC
Evaluation
Metrics: Accuracy, F1-score, ROC-AUC
Validation: 70/30 train-test split

Requirements:
pandas, numpy, scikit-learn, xgboost, imbalanced-learn, matplotlib, seaborn
🔮 Next Steps
Add temporal & weather-based features
Benchmark with LightGBM / CatBoost
Use SHAP for feature importance & interpretability
Deploy as a REST API for real-time predictions
👩‍💻 Author: Priya — Data Scientist with a taste for forward-thinking AI.
