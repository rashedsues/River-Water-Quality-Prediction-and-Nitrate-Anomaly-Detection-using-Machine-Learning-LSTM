# River-Water-Quality-Prediction-and-Nitrate-Anomaly-Detection-using-Machine-Learning-LSTM
# 🌊 River Water Quality Prediction and Nitrate Anomaly Detection

This project applies machine learning and deep learning models to assess and forecast river water safety based on nitrate levels. It includes classical models (XGBoost, Random Forest) and an LSTM neural network for time-series forecasting.

---

## 📁 Contents

### Datasets
- `ML_Water_Quality_Dataset.csv`: Simulated river water measurements (nitrate, flow, temp, pH) at 100 locations over 5 days.
- `Nitrate_With_Anomalies.csv`: Same as above, with injected anomaly points for model testing.

### Notebooks
- `XGBoost_Regression.ipynb`: Predicts nitrate concentration using XGBoost.
- `RandomForest_Classifier.ipynb`: Classifies water as Safe or Unsafe using nitrate level.
- `LSTM_Anomaly_Detection.ipynb`: Predicts future nitrate using LSTM and detects anomalies using rolling Isolation Forest.

---

## 🌍 Environmental Science Applications

This project is a **proof of concept** for how machine learning can help:
- ✅ Detect pollution events in near real-time (nitrate spikes)
- ✅ Forecast water quality days ahead using weather, flow, and chemistry
- ✅ Support early warning systems for contamination (e.g., in agriculture zones)
- ✅ Monitor river health using low-cost sensor data + AI
- ✅ Assist water authorities in making decisions about public safety and irrigation

By combining spatial and temporal data, models like these can be deployed in real-world settings using IoT sensors to track water quality **across river networks**.

---

## 🚀 Getting Started

1. Clone or download this repository
2. Run any of the notebooks in Jupyter or Google Colab
3. Upload either dataset depending on the task
4. Visualize predictions, feature importance, and anomaly alerts

---

## 🧠 Techniques Used

- XGBoost Regression
- Random Forest Classification
- LSTM Neural Network
- Isolation Forest Anomaly Detection
- Data Scaling, Visualization, Lag Features
