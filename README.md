<h1 align="center">🛡️ Bitcoin Attack Prediction Using Machine Learning</h1>

This project focuses on detecting and classifying ransomware-related Bitcoin transactions using machine learning techniques. It leverages the **BitcoinHeist** dataset and a combination of classification models to predict the ransomware family involved in each transaction.

---

## 📌 Project Objective

To build a predictive system that classifies Bitcoin transactions as benign or associated with known ransomware families. The goal is to aid cybersecurity efforts by flagging suspicious wallet activity on the blockchain.

---

## ⚙️ Features

- ✅ Preprocesses the **BitcoinHeist** dataset (2009–2018)
- ✅ Trains models like:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost
  - Voting Classifier
- ✅ Combines models using a **Voting Classifier** for improved accuracy
- ✅ Offers a minimal **Flask-based web interface** for live predictions
- ✅ Outputs the predicted ransomware family (or benign)

---

## 🧰 Tech Stack

| Category        | Technology                          |
|----------------|--------------------------------------|
| Language        | Python                              |
| ML Libraries    | scikit-learn, XGBoost                |
| Data Analysis   | pandas, NumPy, matplotlib, seaborn   |
| Web Framework   | Flask                               |
| Environment     | Jupyter Notebook / IDE              |

---

## 📁 Dataset

- **Source**: [Kaggle - BitcoinHeist Ransomware Dataset](https://www.kaggle.com/datasets/kevin2453/bitcoinheist)
- **Samples**: ~159,000 transactions
- **Labels**: Ransomware families like `Crypto`, `Locky`, `Cerber`, `CryptoLocker`, `CryptoWall`, and `white` (benign)

---

## 🧪 Model Pipeline

1. Load and clean the dataset
2. Feature scaling and label encoding
3. Train multiple ML classifiers
4. Evaluate using accuracy, precision, recall, F1-score
5. Deploy best model using Flask

---
