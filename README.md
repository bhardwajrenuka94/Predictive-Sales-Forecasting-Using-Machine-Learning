# Predictive-Sales-Forecasting-Using-Machine-Learning

## 📌 Project Overview
This project focuses on forecasting sales (demand) using historical and environmental data.
Accurate sales forecasting helps businesses optimize inventory, staffing, and supply chain decisions.

The project applies machine learning regression models to predict demand based on
time-based, weather, and operational features.

---

## 🎯 Business Problem
Retail and service-based businesses often struggle with:
- Over-stocking or under-stocking inventory
- Poor workforce planning
- Inaccurate demand estimation

This project builds a predictive model to estimate future demand and support
data-driven business decisions.

---

## 📊 Dataset Description
The dataset contains hourly demand data with the following features:

- **season** – Season of the year  
- **year** – Year indicator  
- **month** – Month  
- **hour** – Hour of the day  
- **holiday** – Whether the day is a holiday  
- **weekday** – Day of the week  
- **workingday** – Working day indicator  
- **weather** – Weather condition  
- **temp** – Temperature  
- **feel_temp** – Feels-like temperature  
- **humidity** – Humidity level  
- **windspeed** – Wind speed  
- **count** – Total demand (Target variable)

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---

## ⚙️ Project Workflow
1. Data loading and inspection  
2. Data preprocessing and cleaning  
3. One-hot encoding of categorical variables  
4. Train-test split  
5. Baseline model: Linear Regression  
6. Advanced model: Random Forest Regressor  
7. Model evaluation using MAE, RMSE, and R²  
8. Feature importance analysis  
9. Business insights and conclusions  

---

## 📈 Model Performance
- Random Forest significantly outperformed Linear Regression
- Time-based and weather features strongly influenced demand
- The model effectively captures non-linear demand patterns

---

## 💡 Key Business Insights
- Hour and temperature are the strongest demand drivers
- Weather and humidity significantly affect sales volume
- The model can be used for inventory planning and workforce optimization

---

## 🚀 Future Improvements
- Time-series forecasting models (ARIMA, Prophet)
- Hyperparameter tuning
- Model deployment using Flask or FastAPI
- Real-time demand prediction dashboard

---

## 👤 Author
Renuka Bhardwaj
Aspiring Data Scientist
