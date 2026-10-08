# UPI Transactions 2024: Data Analysis & Fraud Detection

A data analysis project on 250,000 UPI (Unified Payments Interface) transactions from 2024, covering:

- Most used transaction types
- Spending patterns by age group, state, bank, month, hour and day of the week
- Transaction success vs failure by network type
- Fraud detection using machine learning models (Logistic Regression, Random Forest)

## Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Files

- `UPI_Transactions.ipynb`: main notebook with all analysis, visualisations and modelling.
- `DataSets/upi_transactions_2024.csv`: the dataset (250k rows, 17 columns).
- `PROJECT_EXPLAINED.txt`: step-by-step explanation, definitions and KPIs.
- `requirements.txt`: Python libraries needed.

## Getting Started

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook UPI_Transactions.ipynb
```

## Data Source

Kaggle: [UPI Transactions 2024 Dataset](https://www.kaggle.com/datasets/skullagos5246/upi-transactions-2024-dataset)
