# ✈️ Flight Delay Prediction — XGBoost & Balanced Random Forest

Predicting flight delays before they happen using historical airline data and modern ML techniques.

---

## 🚀 Overview  
This project tackles a real-world classification problem: **predicting whether a flight will be delayed by 60+ minutes**.  
Using a mix of exploratory analysis, feature engineering, and tree-based ensemble models, it delivers interpretable and high-performance predictions.

---

## 🧩 Approach  
1. **Data Wrangling**  
   - Converted `Date` → extracted `month` & `day`  
   - Encoded categorical columns (`Airline`, `Origin`, `Dest`)  
   - Created binary target `is_delayed_60+`  

2. **Modeling**  
   - **Balanced Random Forest** → handled class imbalance  
   - **XGBoost (tuned with GridSearchCV)** → optimized for ROC-AUC  

3. **Evaluation**  
   - Metrics: Accuracy, F1-score, ROC-AUC  
   - Validation: 70/30 train-test split  

---

👩‍💻 Author: Priya — Data Scientist with a taste for forward-thinking AI
📜 License: MIT

## ⚙️ How to Run  
```bash
git clone <repo-url>
cd flight-delay-prediction
pip install -r requirements.txt
jupyter notebook "Flight-Delay-Prediction- DT-XGGoost.ipynb"

