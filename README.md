# Banking Product Propensity

Individual academic data-science project by **Federico Axel Pucci**, UNLaM, 2026.

**Python · pandas · NumPy · scikit-learn · Classification · Feature engineering**

The notebook explores a customer-month dataset and estimates the probability of acquiring a premium banking product. It includes data cleaning, feature engineering, classifier comparison, cross-validation, hyperparameter tuning and CSV prediction export.

## Run

```bash
python -m venv .venv
python -m pip install -r requirements.txt
python -m jupyterlab
```

Activate the virtual environment before installing. Open `propensity-model.ipynb` and provide the course datasets alongside it:

- `bank_product_propensity_dataset.csv`
- `bank_product_propensity_predict.csv`

The datasets are not redistributed here. The notebook is published without saved outputs, customer records or generated prediction files. The alternative `random-forest-xgboost.ipynb` preserves the Random Forest/XGBoost version of the same assignment. The portfolio copy also adds the missing Random Forest import used by the ablation cell in `propensity-model.ipynb`.

This is an academic modeling exercise. The publication review checks notebook structure and code syntax; it does not claim a new training run or validated production model metrics.
