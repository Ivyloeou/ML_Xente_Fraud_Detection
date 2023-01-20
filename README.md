# __🔎 Xente Fraud Detection Challenge__

🎯 Our goal: Accurately classify the fraudulent transactions from Xente's e-commerce platform and save money.

The data used for this is provided from this website: [Xente Fraud Detection dataset](https://zindi.africa/competitions/xente-fraud-detection-challenge/data).

Xente is an e-commerce and financial service app serving 10,000+ customers in Uganda. This dataset includes a sample of approximately 140,000 transactions that occurred between 15 November 2018 and 15 March 2019.

Our Evaluation Metric: F1-score

This challenge is a great exercise for classification problems and this notebook used various classification models, SMOTE sampling technique and Ensemble methods to improve the F1 score results. 

__📄 Contents:__

- EDA and feature engineering
- Baseline model
- Logistic regression
- Decision tree
- Random forest
- SMOTE
- SMOTE with random forest
- Ensemble methods
- Loss prevented by using our final model
- Error Analysis


---
## Requirements and Environment

Requirements:
- pyenv with Python: 3.9.8

Environment: 

For installing the virtual environment you can either use the Makefile and run `make setup` or install it manually with the following commands: 

```Bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
pip install imbalanced-learn
```
