# Credit-Card-Application-Fraud-Detection
# **Project Overview**

This project focused on developing a **real-time machine learning model** to detect fraudulent credit card transactions.

With over **98,000 transactions** of which only **2.5% were fraudulent**  the challenge lay in tackling **class imbalance**, engineering meaningful behavioral features, and achieving high precision without overwhelming investigators with false positives.

Through a combination of **advanced feature engineering**, **feature selection**, and **model comparison**, I built and evaluated multiple algorithms including Decision Trees, Random Forests, LightGBM, Neural Networks, and XGBoost.

The **final XGBoost model** achieved a **Fraud Detection Rate (FDR@5%) of 66%** on unseen data, identifying nearly one-third of all fraud cases within the top 5% of transactions — translating to an estimated **annual savings of $54.1 million**.

This project demonstrates how **data science and financial analytics** intersect to create tangible business impact through automation, model interpretability, and optimized operational thresholds.

### **Approach and Process**

1. **Data Preparation:**
    - Cleaned 98K transaction records, removed outliers and non-purchase entries, and imputed missing geographic fields.
2. **Feature Engineering:**
    - Created 5,000+ behavioral and temporal features capturing velocity, recency, and diversity patterns.
3. **Feature Selection:**
    - Used KS statistic filtering and CatBoost-based wrapper selection to narrow down to 20 high-impact predictors.
4. **Model Development:**
    - Compared multiple algorithms (Decision Tree, Random Forest, LightGBM, Neural Network, XGBoost).
    - Selected **XGBoost** for best generalization and performance (OOT FDR@5% = **66%**).

### **Results and Recommendations**

- Detected **30.1% of fraud cases within the top 5%** of scored transactions.
- Estimated **annual fraud savings of $54.1M** after financial simulation.
- Recommended cutoff at 5% to balance precision and review costs.

---

### **Reflections**

This project demonstrated the power of feature engineering and model interpretability in risk analytics.

It reinforced the importance of operational realism — building a model that performs consistently across time and business segments.
