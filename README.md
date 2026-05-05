# Building-Energy-Consumption-Prediction
A machine learning project to predict building energy consumption  using historical usage data and environmental features — built in  Python with a full pipeline from raw data to model evaluation.

# ⚡ Building Energy Consumption Prediction

A machine learning project to predict building energy consumption using historical usage data and environmental features — built in Python with a full pipeline from raw data to model evaluation.

---

## 📌 Project Overview

Energy consumption forecasting helps building managers and facility teams plan usage, reduce costs, and improve efficiency. This project builds and evaluates multiple regression and machine learning models to predict energy consumption based on factors like temperature, humidity, time of day, and historical usage patterns.

---

## 🔄 Project Pipeline

1. **Data Collection** — historical energy usage and environmental data
2. **Data Cleaning** — handling missing values, outliers, and format issues
3. **Exploratory Data Analysis (EDA)** — understanding distributions, correlations, and trends
4. **Feature Engineering** — creating meaningful input features for the models
5. **Model Training** — training and comparing multiple models
6. **Model Evaluation** — scoring models on test data using R², MAE, RMSE

---

## 🧹 Data Cleaning & EDA

- Removed null and duplicate records
- Detected and handled outliers in energy readings
- Visualised consumption trends by time of day, day of week, and season
- Computed correlation matrix to identify most predictive features

---

## 🤖 Models Used

| Model | Type |
|-------|------|
| Linear Regression | Baseline regression |
| Random Forest Regressor | Ensemble / tree-based |
| Gradient Boosting Regressor | Boosted ensemble |

---

## 📈 Results

- Best performing model: **Gradient Boosting Regressor**
- R² Score: > 0.85 on test data
- Evaluation metrics: R², Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computations |
| Scikit-learn | Model training and evaluation |
| Matplotlib / Seaborn | Data visualisation and EDA plots |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```
building-energy-prediction/
├── data/
│   └── energy_data.csv          # Raw dataset
├── notebooks/
│   └── energy_prediction.ipynb  # Main Jupyter notebook
├── outputs/
│   └── model_results.png        # Evaluation charts
└── README.md
```

---

## 💡 Key Takeaways

- Gradient Boosting outperformed Linear Regression significantly, showing the value of ensemble methods for this type of data
- Time-based features (hour of day, day of week) were among the strongest predictors
- Proper feature engineering improved model R² by ~15% over the baseline

---

## 👤 Author

**Animesh Vyavahare** — MSc Business Intelligence, HWR Berlin
📧 animeshvyavahare88@gmail.com
