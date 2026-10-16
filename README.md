# Ecommerce Customer Spend Prediction

Jupyter notebooks that explore and compare Linear Regression and XGBoost Regression on the Ecommerce Customers dataset. The target is **Yearly Amount Spent**; the models use session length, time in app, time on website, and membership length as features.

## Notebooks

- `linear_reg.ipynb` — exploratory analysis and a scikit-learn Linear Regression baseline.
- `xgboost_reg.ipynb` — XGBoost regression on the same target and feature set.

Both notebooks drop the dataset's `Email`, `Address`, and `Avatar` columns before modeling.

## Run locally

The dataset file `Ecommerce Customers` is included in the repository and is loaded by that filename.

```bash
git clone https://github.com/sparsh0106/Regression-Analysis-of-Ecommerce-Customers.git
cd Regression-Analysis-of-Ecommerce-Customers
python -m pip install pandas numpy seaborn matplotlib scikit-learn xgboost jupyter
jupyter notebook
```

Open either notebook and run its cells from top to bottom.

## Scope

This is an educational modeling exercise. Its results depend on the notebook's train/test split and should not be treated as a production forecast.
