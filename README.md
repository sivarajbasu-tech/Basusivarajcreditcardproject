# Credit Card Fraud Detection

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
The dataset is highly imbalanced, reflecting real-world banking scenarios where fraudulent transactions are rare but costly.  
The objective is to minimize false negatives by prioritizing recall and F1-score rather than accuracy.

---

## 🎯 Objective
- Identify fraudulent credit card transactions
- Handle extreme class imbalance
- Build a reliable fraud detection model suitable for banking and fintech use cases

---

## 📊 Dataset
- Source: Real-world anonymized credit card transaction data
- Total transactions: 280,000+
- Features:
  - `V1`–`V28`: PCA-transformed features
  - `Time`: Time elapsed between transactions
  - `Amount`: Transaction amount
  - `Class`: Target variable  
    - `0` → Legitimate transaction  
    - `1` → Fraudulent transaction

---

## ⚙️ Methodology
1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Feature scaling using StandardScaler  
4. Train-test split  
5. Model training using Logistic Regression  
6. Model evaluation using:
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix  

---

## 🧠 Model & Evaluation
- **Model Used**: Logistic Regression
- **Why not Accuracy?**
  - Due to class imbalance, accuracy is misleading
  - Focused on recall to reduce missed fraud cases
- Evaluation metrics emphasize real-world fraud detection performance

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📈 Key Learnings
- Handling imbalanced datasets in real-world financial problems
- Importance of recall and F1-score in fraud detection
- Understanding business impact of false negatives in banking systems

---

## 🚀 Future Improvements
- Apply SMOTE or other resampling techniques
- Implement tree-based models (Random Forest, XGBoost)
- Perform hyperparameter tuning
- Add cost-sensitive learning

---

## 📁 Repository Structure
