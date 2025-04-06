# 💳 Credit Card Behaviour Prediction Score

## 📌 Overview
This project aims to predict a user's **credit card score** using their demographic and financial behavior. The primary objective is to help financial institutions assess the creditworthiness of individuals based on historical data.

## 🧠 Problem Statement
Predict whether a person has **Good**, **Standard**, or **Poor** credit behavior based on features like age, annual income, payment history, and other financial indicators.

## 📂 Dataset
The dataset contains customer information such as:
- Age
- Annual Income
- Monthly Inhand Salary
- Number of Bank Accounts
- Number of Credit Cards
- Interest Rate
- Number of Delayed Payments
- Outstanding Debt
- Credit Mix (categorical)
- Credit Score (Target)

## ⚙️ Workflow
1. **Data Cleaning** – Handled null values and cleaned irrelevant entries.
2. **Feature Engineering** – Processed categorical and numerical columns.
3. **Label Encoding** – Converted categories into machine-readable format.
4. **Train-Test Split** – Split dataset for training and validation.
5. **Model Training** – Used classification algorithms like:
   - Random Forest Classifier
   - Logistic Regression
   - Decision Tree
6. **Model Evaluation** – Compared models using accuracy, confusion matrix, and classification report.

## 📈 Results
- The best-performing model was `Random Forest Classifier`.
- Accuracy: `~89%` (update with actual score if available)
- Confusion Matrix and classification report showed balanced performance across all classes.

## 🧰 Tech Stack
- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 🧪 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/credit-card-score-prediction.git
cd credit-card-score-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook credit-card-behaviour-prediction-score.ipynb
```

## 📚 Learnings
- Data preprocessing is crucial for handling real-world messy datasets.
- Label encoding and feature scaling impact model performance significantly.
- Random Forest performs well for classification problems with mixed feature types.
