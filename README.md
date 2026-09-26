🤖 Lab 6: Logistic Regression & KNN — Telco Customer Churn
📌 Overview

This lab builds on Labs 3–4 (Decision Tree & Random Forest) by training two new classifiers — Logistic Regression and K-Nearest Neighbors (KNN) — on the same Telco Customer Churn dataset, and comparing all four models side by side for the first time in the course.

👤 Author
Name: Manahil Fatima
Kaggle Dataset: Telco Customer Churn
📂 Dataset
Name: Telco Customer Churn
Target variable: Churn (Yes/No)
File used: clean_churn.csv (cleaned in Lab 2)
🧠 What's Inside
Part	Focus
1️⃣	Problem Definition & Dataset Verification
2️⃣	Feature Scaling & Preparation
3️⃣	Logistic Regression
4️⃣	KNN & Choosing K
5️⃣	Model Comparison (4 Models)
6️⃣	Coefficient Interpretation
7️⃣	Final Model Selection & Conclusion
⚙️ Tools & Libraries
🐍 Python 3
🐼 Pandas & NumPy
📊 Matplotlib
🔬 scikit-learn (LogisticRegression, KNeighborsClassifier, StandardScaler)
📈 Key Results
Metric	Decision Tree (Lab 3)	Random Forest - Tuned (Lab 4)	Logistic Regression (Lab 6)	KNN (Lab 6)
Accuracy	0.7942	0.8048	0.8070	0.7729
Precision	0.6313	0.6623	0.6584	0.5758
Recall	0.5401	0.5401	0.5668	0.5481
F1-score	0.5821	0.5950	0.6092	0.5616

🏆 Best K for KNN: 11 (best trade-off between accuracy and F1)

✅ Final Model

🎯 Logistic Regression — best F1-score and recall across all four models, making it the strongest choice for catching churners given the ~73/27 class imbalance.

🔑 Top Churn Drivers (Odds Ratios)
⏳ tenure ↓ churn odds — longer tenure = far less likely to churn
🌐 Fiber optic internet ↑ churn odds ~2.17×
📄 Two-year contracts ↓ churn odds by ~44%
💳 Electronic check ↑ churn odds slightly
