# 💳 Credit Card Fraud Detection using Supervised Machine Learning
## DATASET LINK:
Kaggle Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud 
## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques. Since fraud detection datasets are highly imbalanced, the project emphasizes appropriate evaluation metrics such as Precision, Recall, F1-Score, PR-AUC, and ROC-AUC instead of relying only on accuracy.

The notebook covers the complete machine learning workflow, from data preprocessing to model evaluation and comparison.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions.
- Handle highly imbalanced datasets.
- Compare multiple supervised learning algorithms.
- Evaluate models using suitable performance metrics.
- Understand the business impact of False Positives and False Negatives.

---

## 📂 Dataset

- **Dataset:** Credit Card Fraud Detection Dataset
- **Target Column:** `Class`
  - `0` → Legitimate Transaction
  - `1` → Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Performance Comparison
10. Conclusion

---

## 🤖 Machine Learning Models

The notebook includes supervised learning models such as:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes

*(Models may vary depending on the notebook implementation.)*

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC
- PR-AUC

Since fraud detection is an imbalanced classification problem, Precision, Recall, F1-Score, and PR-AUC are considered more reliable than Accuracy.

---

## 📚 Concepts Covered

- Class Imbalance
- Precision vs Recall
- False Positives & False Negatives
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- PR-AUC vs ROC-AUC
- Random Undersampling
- SMOTE Oversampling
- Class Weight Balancing

---

## 📁 Project Structure

```
FraudDetection_SupervisedLearning.ipynb
README.md
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 📌 Key Learnings

- Why accuracy is misleading for imbalanced datasets.
- Importance of Precision and Recall in fraud detection.
- Different techniques for handling class imbalance.
- Comparing supervised machine learning models.
- Selecting the best model using multiple evaluation metrics.

---

## 👨‍💻 Author

**Tirth Patel**

AI & Machine Learning Student

---
