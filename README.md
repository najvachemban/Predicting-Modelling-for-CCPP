# ⚡ Predicting Modelling for Combined Cycle Power Plant (CCPP)

**Team Access Denied**  
A Machine Learning case study on optimizing energy output prediction in Combined Cycle Power Plants using XGBoost and SHAP analysis.

---

## 👥 Team Members

| Name                    | Roll No       | Department     |
|-------------------------|---------------|----------------|
| Jumana Faby Khan        | B230365EC     | ECE            |
| Najva C                 | B230442EC     | ECE            |
| Sahla Muhammed Aslam    | B230701CE     | Civil          |

---

## 📌 Project Overview

This project tackles inefficiencies in Combined Cycle Power Plants by predicting net electrical output (PE) based on key environmental variables. The goal is to help optimize operations and reduce fuel costs using advanced regression models.

---

## 📊 Dataset

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant)
- 9,568 hourly observations
- Features:
  - Ambient Temperature (AT)
  - Exhaust Vacuum (V)
  - Ambient Pressure (AP)
  - Relative Humidity (RH)
  - Energy Output (PE)

---

## 🔍 Key Findings

- Ambient Temperature and Exhaust Vacuum are the most influential variables.
- High temperatures above 25°C reduce power output by ~25.3 MW.
- Vacuum pressures outside 40–60 hPa degrade turbine efficiency.

---

## 🤖 Model Development

| Model               | R² Score | RMSE (MW) |
|--------------------|----------|-----------|
| Linear Regression  | 0.93     | ~5.32     |
| XGBoost (Final)    | 0.96     | 3.44      |

- **XGBoost** outperformed baseline by capturing non-linear relationships.
- SHAP analysis validated feature importance.

---

## 💰 Business Impact

- Annual Energy Output: ~3,980,237 MWh
- Original Fuel Cost: ₹10,448 million
- Estimated Cost Savings: **₹1,960 crore (~$244 million/year)** by optimizing output prediction.

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- XGBoost
- SHAP
- Matplotlib / Seaborn / Pandas / NumPy
- Scikit-learn

---

## 📁 Project Structure

