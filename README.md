💳 Credit Card Fraud Detection (Machine Learning)

A machine learning project to detect fraudulent credit card transactions using five models — Logistic Regression, Random Forest, XGBoost, LightGBM, and CatBoost — and compare their performance.

🚀 Features

Handles imbalanced data using SMOTE

Trains & compares 5 ML algorithms

Evaluates with Accuracy, Precision, Recall, F1, and ROC-AUC

Saves the best model (.pkl) for deployment

⚙️ Tech Stack

Language: Python
Libraries: pandas, numpy, scikit-learn, imbalanced-learn, xgboost, lightgbm, catboost, matplotlib, seaborn

🧠 How to Run
pip install -r requirements.txt
python creditcard_fraud_comparison.py


Dataset: Kaggle - Credit Card Fraud Detection

Place creditcard.csv in the same folder.

📊 Results
Model	ROC-AUC
Logistic Regression	0.965
Random Forest	0.982
XGBoost	0.986
LightGBM	0.989
CatBoost	0.993 ✅
📁 Output

best_model.pkl

scaler.pkl

model_comparison_results.csv

🧩 Future Scope

Real-time fraud detection via Flask/Streamlit

Integration with banking APIs

Deep learning and hybrid models
