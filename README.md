# 🌍 Global Weather Forecast Analysis

## 📚 Project Overview
This project focuses on forecasting global weather trends using advanced data science techniques. The goal was to analyze a comprehensive weather dataset, build multiple forecasting models, and derive actionable insights related to climate patterns and environmental impacts.

---

## 📊 Dataset Description
- **Source:** [Kaggle - Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code)  
- **Features:** Over 40 features including temperature, humidity, wind speed, air quality indices (PM2.5, PM10), and geographical details.  
- **Time Period:** Historical daily weather data for cities worldwide.

---

## ⚙️ Methodology

### 1. Data Cleaning & Preprocessing
- **Handled Missing Values** by filling with appropriate statistical measures.  
- **Outlier Detection** using Isolation Forest to remove anomalies.  
- **Normalization** where necessary for model compatibility.

### 2. Exploratory Data Analysis (EDA)
- Identified trends, correlations, and patterns in temperature and precipitation.  
- Conducted anomaly detection and spatial analysis.  
- Visualized temperature trends and geographical weather distributions.

### 3. Forecasting Models
- **ARIMA Model:** Built for time-series forecasting based on past temperature data.  
- **Prophet Model:** Implemented for flexible and intuitive forecasting.  
- **Ensemble Model:** Combined ARIMA and Prophet predictions for improved accuracy.  
- **Evaluation Metrics:** Used MAE and RMSE for model performance evaluation.

### 4. Unique Analyses
- **Feature Importance:** Identified key factors affecting temperature using Random Forest Regressor.  
- **Environmental Impact:** Analyzed correlations between temperature and air quality metrics like PM2.5 and PM10.

---

## ✅ Key Results & Insights
- The **Ensemble Model** provided the most accurate forecasts.  
- **Humidity** and **air quality metrics** significantly influenced temperature trends.  
- A moderate correlation was observed between air quality indices and temperature changes.

---

## 🚀 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com/MITNIK27/global-weather-forecast-analysis.git
2. **Install required packages:**
   ```bash
   pip install -r requirements.txt
3.Run the Jupyter Notebook to execute analyses and models.

## 📄 Conclusion
   This project effectively demonstrates advanced data science skills, from data cleaning and exploration to model building      and evaluation. The insights derived provide a strong foundation for understanding global weather trends and their            environmental impacts.
## 📞 Contact
For any queries, please contact:
- Paarth Sahni
- paarthsahni112@gmail.com
