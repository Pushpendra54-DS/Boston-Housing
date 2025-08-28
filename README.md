# Boston Housing — Regression Models
# Boston Housing — Regression Models (Linear, Random Forest, XGBoost)

This project predicts Boston house prices using three machine learning models:  
**Linear Regression, Random Forest, and XGBoost**.

---

## 📂 Project Structure
├── data/ # dataset(s) or link
├── notebooks/ # Jupyter notebooks (EDA & models)
├── scripts/ # Python scripts (training, prediction)
├── results/ # Plots & evaluation metrics
├── requirements.txt # Project dependencies
├── .gitignore # Ignore unnecessary files
└── README.md

## Data Used

- Dataset: [`boston_housing.csv`](data/boston_housing.csv)

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

## ▶️ How to Run
1. Clone this repo  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
