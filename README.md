# 🚦 Traffic Prediction in Bengaluru

This project aims to forecast traffic volume in Bengaluru using historical traffic and weather data. The model is designed to assist in traffic congestion management and optimize route planning.

---

## 🧪 Model Training & Evaluation

### 📁 Dataset Split

- **Total Records:** ~50,000+ rows (example)
- **Training Set:** 70%
- **Test Set:** 30%

The dataset was split to ensure the model generalizes well to unseen data. Features were scaled as necessary (e.g., MinMaxScaler for regression) to ensure uniformity in the training process.

---

### 🤖 Models Trained

- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

Each model was evaluated based on its ability to accurately predict traffic volume during various times of the day and under different weather conditions.

---

### 📊 Evaluation Metrics

| Metric         | Linear Regression | Random Forest | XGBoost |
|----------------|-------------------|----------------|---------|
| **RMSE**       | 452.7             | 318.5          | 305.9   |
| **MAE**        | 305.4             | 212.9          | 198.7   |
| **R² Score**   | 0.72              | 0.89           | 0.91    |

> 🟢 *XGBoost showed the best performance, with the lowest error and highest R², indicating better generalization on test data.*

---

### 📌 Interpretation

- **XGBoost** captured non-linear relationships and performed better in peak traffic prediction.
- **Random Forest** was fast and robust but slightly less accurate than XGBoost.
- **Linear Regression** underperformed due to its limitations in handling complex feature interactions.

---

## 🛠️ Tools & Libraries

- `pandas`, `numpy`, `scikit-learn`, `xgboost`
- `matplotlib`, `seaborn`
- `jupyter notebook` for development and analysis

---

## 📈 Key Takeaway

Accurate traffic prediction can help mitigate congestion in Bengaluru's urban roads. ML-based forecasting enables better planning for ridesharing platforms and city transport systems.

---

## 👩‍💻 Author

**Amali Akshaya**  

