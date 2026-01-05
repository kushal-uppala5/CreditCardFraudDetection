# Credit Card Fraud Detection 💳🚨

## 📌 Project Overview
Credit card fraud detection is a critical problem in the financial industry. This project focuses on identifying fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, making it essential to use appropriate data preprocessing and evaluation strategies.

The project demonstrates the use of both **undersampling** and **oversampling** techniques to handle class imbalance and compares their impact on model performance.

---

## 🧠 Problem Statement
Fraudulent transactions represent a very small fraction of total transactions, which makes fraud detection a challenging classification problem.

**Objectives:**
- Detect fraudulent credit card transactions accurately
- Handle class imbalance using sampling techniques
- Evaluate models using precision, recall, and F1-score instead of accuracy alone

---

## 📂 Dataset
- **Dataset Name:** Credit Card Fraud Detection
- **Source:** Kaggle
- **Dataset Link:**  
  👉 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### 📊 Dataset Description
- Contains transactions made by European cardholders in September 2013
- Total transactions: **284,807**
- Fraudulent transactions: **492**
- Features `V1` to `V28` are anonymized using PCA
- Important columns:
  - `Time` – Seconds elapsed between transactions
  - `Amount` – Transaction amount
  - `Class`:
    - `0` → Legitimate
    - `1` → Fraud


---

## 🛠️ Technologies & Tools Used
- Python 
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (`imblearn`)

---

## 🔍 Project Workflow
1. Importing libraries and loading the dataset
2. Exploratory Data Analysis (EDA)
3. Data preprocessing and feature scaling
4. Handling class imbalance using:
   - Undersampling
   - Oversampling
5. Model training
6. Model evaluation using:
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix

---

## 📊 Model Evaluation
Due to the imbalanced nature of the dataset, model performance is evaluated using:
- **Recall** (to reduce false negatives)
- **Precision**
- **F1-score**
- **Confusion Matrix**

Accuracy alone is not a reliable metric for fraud detection problems.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/CreditCardFraudDetection.git
```

---

### 2️⃣ Navigate to the Project Directory
```bash
cd CreditCardFraudDetection
```

---

### 3️⃣ Install Required Libraries


Make sure Python is installed, then run:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

---

### 4️⃣ Download the Dataset

Download creditcard.csv from Kaggle

Place it in the project root directory

---

### 5️⃣ Run the Jupyter Notebook
```bash
jupyter notebook CreditCardFraudDetection.ipynb
```

---


## 📌 Results

The model demonstrates strong performance in detecting fraudulent transactions, especially when sampling techniques are applied. Oversampling improves recall, while undersampling reduces training time. A comparison of both approaches is included in the notebook.

---

## 📁 Project Structure
├── CreditCardFraudDetection.ipynb  
├── README.md  
└── creditcard.csv  

---

## 👤 Author

Kushal Uppala  
Computer Science Engineering(AI&ML)


---

## ⭐ Acknowledgements

Kaggle for providing the dataset

Scikit-learn and Imbalanced-learn documentation

Open-source Python community
