# Anomaly-Detection-in-Financial-Transactions

Designed and implemented a fraud detection system using Python and machine learning techniques to identify fraudulent transactions from a highly imbalanced Kaggle dataset (284,807 transactions with only 492 fraud cases). Applied in-depth exploratory data analysis (EDA) to uncover patterns and feature correlations. Used **XGBoost** as the primary classification model for its robustness and handling of imbalanced data.

To address the class imbalance, employed **SMOTE (Synthetic Minority Over-sampling Technique)** to synthetically generate minority class samples. Fine-tuned model thresholds and focused on **precision-recall trade-offs** to optimize for high recall and minimize false negatives — a critical requirement in fraud detection systems.

Achieved **over 95% recall**, ensuring most fraud cases were successfully detected while keeping false alarms under control.

**Tools & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, imbalanced-learn (SMOTE)

**Key Techniques:**

* Data preprocessing & EDA
* Handling class imbalance (SMOTE)
* Model training with XGBoost
* Threshold tuning
* Evaluation using Precision-Recall Curve and F1-score
