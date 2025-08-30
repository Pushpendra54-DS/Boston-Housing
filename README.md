# Boston Housing — Regression Models
# 🏠 Boston Housing Price Prediction

![Python](https://img.shields.io/badge/Python-3.9-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# Boston Housing — Regression Models (Linear, Random Forest, XGBoost)

This project predicts Boston house prices using three machine learning models:  
**Linear Regression, Random Forest, and XGBoost**.
---
## Table of Contents

- [Motivation](#motivation)
- [Project Structure](#project-structure)
- [Dataset Used](#dataset-used)
- [Tech Stack](#tech-stack)
- [Models and Metrics](#models-and-metrics)
- [Visuals](#visuals)
- [How to Run or View](#how-to-run-or-view)
- [Future Work](#future-work)
- [Notebooks](#notebooks)

---

## Motivation

I wanted to compare how three different regression models—Linear Regression, Random Forest, and XGBoost—perform in predicting Boston housing prices, while also learning how to structure and document a data science project clearly.

---

## 📂 Project Structure
├── data/ # dataset(s) or link
├── notebooks/ # Jupyter notebooks (EDA & models)
├── scripts/ # Python scripts (training, prediction)
├── results/ # Plots & evaluation metrics
├── requirements.txt # Project dependencies
├── .gitignore # Ignore unnecessary files
└── README.md

## Dataset Used

- Dataset: [Dataset: boston.csv](./boston.csv)


---

## 🧰 Tech Stack
- Python  
- pandas, numpy  
- scikit-learn (Linear Regression, Random Forest)  
- xgboost  
- matplotlib, seaborn (visualization)  
- joblib (model saving)

---

## 📊 Models and Metrics
We trained and evaluated three models:

| Model           | R² (test) | MAE  |  MSE |
|-----------------|-----------|------|------|
| Linear          | 0.67      | 3.20 | 24.49|
| Random Forest   | 0.92      | 1.89 | 6.20 |
| XGBoost         | 0.92      | 1.89 | 6.20 |




---

## 🖼 Visuals
Plots will be stored in the `results/` folder.  
Examples:  
- Actual vs Predicted  
- Feature Importance  

---

## How to Run or View

### ​ Option 1: View on GitHub
Click any notebook in the `notebooks/` folder to open it directly in your browser—no setup needed.

###  Terminal Option 2: Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/Pushpendra54-DS/Bonston-Housing.git

# 2. Navigate into the project folder
cd Bonston-Housing

# 3. Install the required packages
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook
Once Jupyter opens, navigate to the notebooks/ folder and click a notebook to run it.
```

---
 
## Future Work

- Add cross-validation and hyperparameter tuning to improve model generalization.
- Visualize feature importance and residuals for better model interpretation.
- Build a simple web interface (e.g., with Streamlit or Flask) to make predictions interactively.
- Experiment with neural network models or ensemble stacking for performance comparison.

----

## Notebooks

Click to view each notebook:

- [01 – Linear Regression](notebooks/01-linear_regression.ipynb)
- [02 – Random Forest](notebooks/02-random_forest.ipynb)
- [03 – XGBoost](notebooks/03-xgboost.ipynb)





