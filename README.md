This project builds and evaluates a machine learning model to predict startup success using Crunchbase-style data. 
The model uses XGBoost, a high-performance gradient boosting algorithm, and is trained on a cleaned version of the provided dataset.

The model is trained on features like funding history, location, and industry category, after careful preprocessing to remove data leakage (e.g., columns like acquired and status that reflect outcomes). 
The pipeline includes duplicate removal, missing value imputation, one-hot encoding, and hyperparameter tuning with Optuna. 
