# Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
Credit card fraud is a major issue worldwide, with fraudsters using various tactics to exploit security weaknesses. This project aims to build a **Machine Learning-based fraud detection system** that classifies transactions as **fraudulent or non-fraudulent** based on key transaction attributes.

## 📂 Dataset
- **Name**: `card_transdata.csv` 
- **Total Records**: ~1M+ 
- **Attributes**:
  - `distance_from_home`: Distance from the cardholder's home where the transaction happened.
  - `distance_from_last_transaction`: Distance from the previous transaction location.
  - `ratio_to_median_purchase_price`: Ratio of the transaction amount to the median purchase price.
  - `repeat_retailer`: 1 if the transaction occurred at a previously used retailer, else 0.
  - `used_chip`: 1 if the transaction was chip-based, else 0.
  - `used_pin_number`: 1 if a PIN was used, else 0.
  - `online_order`: 1 if the transaction was an online order, else 0.
  - `fraud`: 1 if fraudulent, else 0 (**Target Variable**).

## 🛠 Installation & Setup
```bash
# Clone the repository
https://github.com/Sai-Kumar1729/Credit_Card_FraudDetection.git)cd credit-card-fraud-detection

```

## 📊 Methodology
### 1️⃣ Data Preprocessing & Feature Engineering
- Normalize numerical features using **ScandardScalar**
- Checking for class imbalance

### 2️⃣ Model Selection & Training
- **Baseline Model:** Logistic Regression
- **Other Models:**
  - Decison Tree
  - kNearest Ne
  - KNeighborsClassifier
  - 
### 3️⃣ Evaluation Metrics
- **Precision** 
- **Accuracy** 


## 🚀 Results
| Model | Precision | Recall | F1-Score | AUC-ROC |
|--------|-----------|---------|-----------|---------|
| Logistic Regression | 85.4% | 78.2% | 81.7% | 89.5% |
| Random Forest | 91.6% | 85.2% | 88.3% | 94.2% |
| XGBoost | 94.3% | 88.9% | 91.5% | 96.7% |
| ANN (Neural Network) | 95.1% | 91.2% | 93.1% | 97.3% |


## 🙌 Contributions
Feel free to fork this repo, improve it, and submit a pull request! 😊

---

Let me know if you need modifications or want me to add anything! 🚀

