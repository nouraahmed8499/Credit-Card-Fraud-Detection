
# Creadit Card Fraud Detection 

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It leverages a real-world dataset from Kaggle containing anonymized transaction data, including features generated through PCA to protect confidentiality.


## Data
download data from **Kaggle** using this path: 
```bash
mlg-ulb/creditcardfraud
```

**creditcard.csv**:
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Run Locally 


Go to the project directory
```bash
  cd 'Credit Card Fraud Detection'
```

Create Virutal Environment (make sure python installed on yout local machine. version = 3.12)
```bash
  python -m venv venv
```

Activate Environment
```bash
  venv\Scripts\activate
```

Install dependencies
```bash
  python pip install -r requirements.txt
```

running the model Notebook
credit-card-fraud-detection.ipynb


