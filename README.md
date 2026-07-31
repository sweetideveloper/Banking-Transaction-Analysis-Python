# 🏦 Banking Transaction Analysis using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a banking transactions dataset using Python. The goal is to analyze customer transactions, identify spending patterns, transaction channels, customer demographics, and account behavior through data cleaning, visualization, and statistical analysis.

---

## 📂 Dataset Information

**Dataset Name:** `bank_transactions_data_2.csv`

### Features

| Column Name | Description |
|-------------|-------------|
| TransactionID | Unique transaction ID |
| AccountID | Customer Account ID |
| TransactionAmount | Amount of the transaction |
| TransactionDate | Date & Time of transaction |
| TransactionType | Credit or Debit |
| Location | Transaction location |
| DeviceID | Device used |
| IP Address | Customer IP Address |
| MerchantID | Merchant Identifier |
| Channel | Transaction Channel (ATM, Online, Branch, etc.) |
| CustomerAge | Customer Age |
| CustomerOccupation | Occupation of customer |
| TransactionDuration | Processing duration |
| LoginAttempts | Number of login attempts |
| AccountBalance | Current account balance |
| PreviousTransactionDate | Previous transaction timestamp |

---

# 🎯 Project Objectives

- Perform data cleaning
- Handle missing values
- Check duplicate records
- Analyze transaction trends
- Analyze customer demographics
- Compare Credit vs Debit transactions
- Identify high-value transactions
- Visualize transaction patterns
- Generate business insights

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📁 Project Structure

```
Banking-Transaction-Analysis/
│
├── data/
│   └── bank_transactions_data_2.csv
│
├── notebooks/
│   └── Banking_Transaction_Analysis.ipynb
│
├── images/
│   ├── transaction_distribution.png
│   ├── transaction_type.png
│   ├── customer_age.png
│   └── correlation_heatmap.png
│
├── README.md
└── requirements.txt
```

---

# 📊 Exploratory Data Analysis

The project includes:

- Dataset Overview
- Data Types
- Missing Value Analysis
- Duplicate Record Check
- Statistical Summary
- Correlation Analysis
- Outlier Detection
- Feature Distribution

---

# 📈 Visualizations

Some visualizations included are:

- Transaction Amount Distribution
- Credit vs Debit Transactions
- Transaction Channel Analysis
- Customer Age Distribution
- Account Balance Distribution
- Occupation-wise Transactions
- Location-wise Transactions
- Correlation Heatmap
- Boxplots for Outlier Detection

---

# 📊 Key Insights

- Identify the most common transaction type.
- Discover the most frequently used transaction channel.
- Analyze customer age distribution.
- Find customers with high account balances.
- Detect unusual transaction amounts.
- Compare average transaction amount by occupation.
- Analyze login attempt patterns.
- Understand transaction frequency across locations.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Banking-Transaction-Analysis.git
```

Go to project folder

```bash
cd Banking-Transaction-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Required Libraries

```txt
pandas
numpy
matplotlib
seaborn
jupyter
```

---

# ▶️ Sample Code

```python
import pandas as pd

df = pd.read_csv("bank_transactions_data_2.csv")

print(df.head())

print(df.info())

print(df.describe())
```

---

# 📌 Future Improvements

- Fraud Detection using Machine Learning
- Transaction Prediction
- Customer Segmentation
- Interactive Dashboard using Streamlit
- Power BI Dashboard
- SQL Integration
- Real-Time Banking Analytics

---

# 📷 Project Preview

Include screenshots of:

- Data Cleaning
- EDA
- Charts
- Heatmaps
- Dashboard (if created)

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Push to GitHub
5. Create a Pull Request

---

# ⭐ If you found this project helpful, don't forget to Star the repository!

---

## 👩‍💻 Author

**Sweeti Yuonate**

- GitHub: https://github.com/sweetideveloper
- LinkedIn: www.linkedin.com/in/sweetideveloper
