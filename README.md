# Impact of Data Balancing Techniques on Market Basket Analysis

**MSc Data Analytics Dissertation — University of Portsmouth**  
**Author:** Bhargava Sai Chiguripati  
**Supervisor:** Dr Dongxu Gao 
**Submitted:** May 2026

---

## 📌 Overview
This study investigates how data balancing techniques affect association rule mining on imbalanced retail transaction data.

## 📦 Dataset
UCI Online Retail Dataset — 27,738 UK transactions, top 150 products

## ⚙️ Methods
- **Balancing:** Oversampling, Undersampling, Hybrid, SMOTE
- **Algorithms:** Apriori & FP-Growth

## 🔑 Key Findings
- Undersampling → best minority coverage (52.2%)
- SMOTE → below baseline (14.6%) — unexpected
- Apriori = FP-Growth (identical rules)
- FP-Growth up to 4.4x faster than Apriori

## 🛠️ Tools
Python, Jupyter Notebook, mlxtend, imbalanced-learn, pandas, scipy
