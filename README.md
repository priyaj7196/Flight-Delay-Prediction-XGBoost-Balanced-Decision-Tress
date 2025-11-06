# ✈️ Flight Delay Prediction — XGBoost, LightGBM & CatBoost

Predicting flight delays before they happen using historical airline data and modern ML techniques.

---

## 🧩 Approach

1. **Data Wrangling**  
   - Converted `Date` → extracted `month` & `day`  
   - Encoded categorical columns (`Airline`, `Origin`, `Dest`)  
   - Created binary target `is_delayed_60+`  
   - Handled class imbalance using **SMOTE** on training data  

2. **Modeling**  
   - **Balanced Random Forest** → baseline for imbalance handling  
   - **XGBoost (GridSearchCV)** → optimized for ROC-AUC  
   - **LightGBM (Optuna)** → efficient and fast gradient boosting  
   - **CatBoost (Optuna)** → handles categorical features natively  

3. **Evaluation**  
   - Metrics: Accuracy, F1-score, ROC-AUC  
   - Validation: 70/30 train-test split  
   - Compared all models for performance and interpretability  

---

👩‍💻 **Author:** Priya — Data Scientist with a taste for forward-thinking AI  
📜 **License:** MIT  

---

## ⚙️ How to Run

```bash
git clone <repo-url>
cd flight-delay-prediction
pip install -r requirements.txt
jupyter notebook "Flight_Delay_Prediction_Using_LGBM_and_CatBoost.ipynb"
