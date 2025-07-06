# insurance-claims-fraud-detection
Machine Learning project to detect fraudulent insurance claims
# 🛡️ Insurance Claim Fraud Detection

This project aims to detect fraudulent insurance claims using machine learning models. By preprocessing real-world data and training multiple classifiers, the project identifies patterns that help distinguish between genuine and fraudulent claims.

---

## 🚀 Project Objectives

- Predict whether an insurance claim is fraudulent.
- Preprocess and encode real-world insurance data.
- Handle class imbalance using SMOTE.
- Compare multiple machine learning models for performance.

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)

---

## 📂 Dataset

- File: `insurance_fraud_large.csv`
- Size: Large dataset with insurance claim records.
- Target Column: `fraud_reported` (Yes/No)

> *Note: The dataset is expected to be in the `data/` folder. If you're running this notebook, make sure the CSV file path is correct.*

---

## 🛠️ Steps Performed

1. **Data Loading and Exploration**
2. **Missing Values Handling**
3. **Feature Selection and Cleaning**
4. **Label Encoding and One-Hot Encoding**
5. **Train-Test Split**
6. **SMOTE for Class Imbalance**
7. **Model Training:**
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost Classifier
8. **Model Evaluation:**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1 Score)
9. **Visualization**
   - Confusion Matrix Heatmap
   - F1 Score Comparison Bar Chart

---

## 📊 Results

| Model              | F1 Score |
|-------------------|----------|
| Logistic Regression | 0.67     |
| Random Forest       | 0.74     |
| XGBoost             | 0.81     |

XGBoost outperforms other models with the highest F1 Score, making it the best candidate for detecting fraud in this case.

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/insurance-claims-fraud-detection.git
   cd insurance-claims-fraud-detection
