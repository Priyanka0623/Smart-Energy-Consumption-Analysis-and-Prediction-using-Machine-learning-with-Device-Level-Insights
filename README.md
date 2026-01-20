---

# ⚡ Smart Energy Consumption Analysis and Prediction

##  Overview
The **Smart Energy System** is designed to analyze household energy consumption patterns and forecast future usage using **machine learning and deep learning models**. It leverages smart meter data to uncover seasonal trends, peak hours, and device-level consumption, while providing **interactive dashboards** and **smart energy efficiency tips**.  

This project demonstrates a **complete ML pipeline**: from data preprocessing and feature engineering to model training, evaluation, visualization, and deployment.

---

## ✨ Key Features
- 📊 **Consumption Insights**: Hourly, daily, weekly, and monthly usage analysis  
- 🔎 **Outlier Handling**: Robust preprocessing using the **Interquartile Range (IQR) method**  
- 🔮 **Forecasting Models**: Baseline Linear Regression and advanced LSTM neural networks  
- 📈 **Model Comparison**: Evaluation with MAE, RMSE, and R² metrics  
- 🖼️ **Interactive Dashboards**: Visualizations with Matplotlib and Chart.js  
- 💡 **Smart Tips Engine**: Actionable recommendations for reducing energy wastage  
- 🌐 **Web Integration**: Flask backend with embedded HTML, CSS, and JavaScript frontend  

---

##  Technologies Used
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras  
- **Frontend**: HTML, CSS, JavaScript (embedded)  
- **Framework**: Flask  
- **Visualization**: Matplotlib, Chart.js  
- **Data Formats**: CSV, JSON  

---

##  Methodology
1. **Data Preprocessing**  
   - Missing value handling (forward/backward fill)  
   - Outlier removal using **IQR method**  
   - Normalization with MinMaxScaler  
   - Resampling to hourly/daily aggregates  

2. **Feature Engineering**  
   - Time-based features: hour, day, month, day_of_week  
   - Lag features: previous hour/day/week consumption  
   - Rolling statistics: moving averages (3h, 24h, 168h)  
   - Device-level aggregations  

3. **Model Development**  
   - Baseline: Linear Regression  
   - Advanced: LSTM neural networks with hyperparameter tuning  
   - Cross-validation for robustness  

4. **Evaluation**  
   - Metrics: MAE, RMSE, R²  
   - Comparison table saved for reproducibility  
   - Visualization of actual vs predicted consumption  

5. **Visualization & Dashboard**  
   - Hourly/Daily/Weekly/Monthly consumption plots  
   - Device-level pie chart of usage distribution  
   - Smart tips generated based on consumption patterns  

6. **Deployment**  
   - Flask backend serving predictions and dashboards  
   - Embedded frontend (HTML, CSS, JS) for user interaction  
   - REST API for real-time energy monitoring  

---

##  Model Performance
| Model                        | MAE   | RMSE  | R²   |
|-------------------------------|-------|-------|------|
| Linear Regression (Baseline) | …     | …     | …    |
| LSTM (Single Split)          | …     | …     | …    |
| LSTM (Cross Validation)      | …     | …     | …    |
| Tuned LSTM                   | …     | …     | …    |

*(Exact values generated during training; comparison table saved in `saved_module5/comparison_table.csv`)*

---

##  Dataset
**SmartHome Energy Monitoring Dataset**  
- Hourly smart meter readings with seasonal patterns and peak hours  
- Device-level consumption (fridge, AC, dishwasher, laundry, microwave, etc.)  
- Time-series ready format for forecasting and analytics  

**Data Format**  
- `timestamp`: Date and time of measurement  
- `device`: Appliance name  
- `consumption_kwh`: Energy consumption in kilowatt-hours  
- `hour`, `day`, `month`, `day_of_week`: Time-based features  
- `lag_1`, `lag_24`, `ma_3`, `ma_24`: Lag and rolling features  

---

##  Future Scope
- Real-time IoT sensor integration  
- Anomaly detection in energy usage  
- Smart home automation features  
- Deployment on cloud platforms for scalability  

---

##  Conclusion
The **Smart Energy System** showcases a **complete end-to-end machine learning pipeline** for energy analytics. By combining **robust preprocessing (IQR method)**, **feature engineering**, **baseline and advanced models**, and **interactive dashboards**, it delivers both **technical depth** and **user-facing clarity**.  


---
