# Detecting Anomalous Corporate Expense Transactions Using Machine Learning

This repository contains a machine learning case study. The goal of the project is to detect fraudulent or anomalous corporate expense transactions using supervised machine learning models.

##Project Overview

Traditional rule-based expense systems often overlook subtle or emerging fraud patterns. This project demonstrates how machine learning can enhance fraud detection in corporate finance workflows, helping teams reduce risk and boost trust.

### Models Used:
- **Decision Tree**
- **Random Forest** (Best performance)

### Tools & Technologies:
- RapidMiner (Modeling)
- Kaggle Dataset

## Dataset

- **Source**: Kaggle – Fraud Detection Dataset
- **Records**: 6,362,620
- **Attributes**: 11 (e.g., `type`, `amount`, `oldbalanceOrg`, etc.)
- **Target**: `isFraud` (binary classification)

> Fraudulent transactions were concentrated in `CASH_OUT` and `TRANSFER` types with unusual balance behavior.

---

## Modeling & Results

| Model          | Accuracy | Precision | Recall | AUC   |
|----------------|----------|-----------|--------|-------|
| Decision Tree  | 99.33%   | 100%      | 33.33% | 0.661 |
| Random Forest  | 99.88%   | 99.91%    | 50.28% | 0.782 |

**Random Forest outperformed Decision Tree**, especially on recall, making it the ideal choice for anomaly detection in real-world corporate settings.

---

## Why It Matters

- Detects hidden or emerging fraud patterns
- Reduces manual audit overhead
- Improves trust and transparency in financial workflows
- Scalable for platforms like Navan

---

## Future Enhancements

- Explore **unsupervised learning** (e.g., Isolation Forest, Autoencoders)
- Apply **NLP** for analyzing expense narratives
- Deploy **real-time dashboards** for anomaly alerts

---


