# 🚦 Traffic Prediction in Bengaluru

This project aims to predict traffic patterns in Bengaluru using historical traffic and weather data. The objective is to support smarter traffic flow management, reduce congestion, and assist platforms like Uber in route planning.

---

## 📌 About the Project

Predicted Bengaluru traffic volume using time, location, and weather-based features. Applied feature engineering, EDA, and regression models to forecast congestion trends.

---

## 📊 Dataset Overview

- **City**: Bengaluru
- **Features**: Date, time, temperature, weather condition, traffic volume
- **Target**: Traffic Volume (vehicles/hour or similar metric)

---

## 🔍 Key Steps

- Data Cleaning & Preprocessing
- DateTime Feature Extraction (hour, day, weekday)
- Weather data integration
- Exploratory Data Analysis (EDA)
- Regression Models: Linear Regression, Random Forest, XGBoost
- Model Evaluation: RMSE, MAE, R² Score

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook
- Power BI *(optional for dashboards)*

---

## 📈 Sample Insights

- Traffic peaks during office hours (8–10 AM, 5–8 PM)
- Rainy weather causes increased congestion
- Weekday traffic is heavier than weekends

---

## 🚀 How to Run

```bash
# Clone this repository
git clone https://github.com/yourusername/bengaluru-traffic-prediction.git

# Navigate into the folder
cd bengaluru-traffic-prediction

# Launch the notebook
jupyter notebook Bengaluru_Traffic_Prediction.ipynb
