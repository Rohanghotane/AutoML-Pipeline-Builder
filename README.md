# AutoML-Pipeline-Builder

A fully automated, configurable machine learning pipeline that parses JSON configuration files to handle preprocessing, feature engineering, feature reduction, model selection, hyperparameter tuning, and result logging.

## 🚀 Project Overview

This project automates the end-to-end machine learning workflow:

1. **Parses the JSON config** — Specify preprocessing, features, models, and parameters.
2. **Handles preprocessing** — Clean missing values, encode categorical data, scale numerical features.
3. **Generates features** — Supports feature engineering based on configuration.
4. **Reduces features** — Uses dimensionality reduction techniques (e.g., PCA, Feature Selection).
5. **Selects and trains models with GridSearch** — Hyperparameter tuning using GridSearchCV.
6. **Logs results** — Stores performance metrics, model parameters, and other useful information.

---

## 🧰 Tech Stack

- **Python 3.8+**
- **Pandas**
- **Scikit-learn**
- **NumPy**
- **JSON**
