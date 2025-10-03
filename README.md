# Customer Lifetime Value (CLV) – Banking

This project estimates the expected lifetime value of banking customers using transaction history, retention/survival features, and regression models. It includes a Jupyter Notebook and a supporting Python script for new‑customer CLV logic.

## Project Contents
- **clv_prediction.ipynb** — Main notebook: data preparation, cohort/retention analysis, feature engineering, model training and evaluation.  
- **CustomerLifetimeValue_Prediction_NewCustomer.py** — Utility script for CLV prediction logic for new customers.  
- **requirements.txt** — Dependencies required to run the notebook.  
- **SPLIT_GUIDE.md** — Notes for mapping files from the original bundle into this repo.

## Features
- Cohort analysis and retention curves  
- Survival/tenure features (time‑to‑event framing)  
- Revenue/monetary feature construction  
- Models: Linear/ElasticNet baselines and tree/boosting options (e.g., Random Forest, XGBoost)  
- Evaluation: MAE, RMSE; simple backtesting/holdout comparison

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```
Open and run `clv_prediction.ipynb`. Update any input paths as needed.

## Notes
- Include only anonymized sample data (or link to external data).  
- Document revenue units/currency and any business‑specific assumptions in the notebook.
