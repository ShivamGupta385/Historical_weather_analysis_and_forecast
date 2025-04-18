# Weather Data Analysis & Forecasting
This project analyzes 25 years of historical weather data for **Jaipur, India** and builds forecasting models to predict key weather indicators. It combines statistical and machine learning models with comprehensive visualizations to derive actionable insights.

## Objectives
- Perform **exploratory data analysis** on daily weather metrics.
- Forecasting key parameters for weather analysis.
- Compare and evaluate **Random Forest**, **XGBoost**, **LightGBM** models.

## Key Features
- 25 years of time-series data.
- Time series decomposition, stationarity checks, and autocorrelation plots.
- Train/test splitting with rolling forecasting.
- Feature engineering for non-linear models.
- Model evaluation using RMSE, MAE, R^2 & Accuracy and visual comparison.
- Feature importance and ensemble methods.

## Dataset
- Format: `.csv`
- Columns:
  1) date –> Timestamp (date/time of the recorded weather data).
  2) precipitation_hours (h) –> Total hours of precipitation (rain/snow) in a given period.
  3) precipitation_sum (mm) –> Total precipitation (rain/snow) in millimeters.
  4) Temperature (°C): mean, max, min (2m height)
  5) Wind Speed (Km/h): mean, max, min (10m height)
  6) Cloud Cover (%): mean, max, min 

- Daily observations from **2000 to 2024**.

## Models Used
| Model                 | Description                                      |
|-----------------------|--------------------------------------------------|      
| **Random Forest**     | Tree-based ensemble regression model             |
| **XGBoost**           | Gradient boosting framework                      |
| **LightGBM**          | Fast, efficient gradient boosting model          |

## Visualizations & Insights
- Rainy vs. Clear Days (Pie chart)
- Temperature Trends Over Time (Line plot & Box plot).
- Precipitation Analysis (Bar plots)
- Monthly Cloud Cover (Stacked Bar plot)
- Wind Chill vs. Temperature (Scatter plot)
- Relationships Between Key Weather Variables (Scatter plot)
- Line plots for actual vs predicted values.
- Feature importance plots for each ML model.
- Model performance comparison using RMSE, R^2, MAE and Accuracy.

## Future Improvements
- Integrate **Prophet** or **deep learning models (e.g., LSTM)** for long-term forecasting.
- Build a **Gradio or Streamlit dashboard** for real-time predictions.
- Expand the dataset to cover other cities or countries.
