# Regression-Analysis-on-Dataset-Renewable-Energy-and-Weather-Conditions
This project explores the relationship between renewable energy output and weather conditions using regression techniques. It implements both LSTM (Long Short-Term Memory) networks and Hidden Markov Models (HMM) to capture the temporal and probabilistic patterns in the data.

🧠 Objectives

Predict renewable energy generation based on meteorological data.

Evaluate model performance using metrics like MAE, MSE, and R² Score.

Compare LSTM and HMM with traditional regression models.

📊 Dataset

The dataset includes hourly records of:

Temperature, humidity, wind speed, precipitation

Global Horizontal Irradiance (GHI)

Day length, sunlight time, and weather types

Energy delta [Wh] as the target variable

⚙️ Methodology

Preprocessing:

Handling missing values

One-hot encoding of categorical data

Feature normalization

Models Used:

LSTM: For time-series prediction of energy generation

HMM: To model hidden weather states affecting energy output

Linear Regression: Used as a baseline

Evaluation:

MAE for LSTM: 170.20, R²: 0.87

MSE for HMM: 138000.34, R²: 0.87

💡 Technologies

Python

Pandas, NumPy, Scikit-learn

TensorFlow/Keras

hmmlearn

📈 Conclusion

LSTM performed best in modeling temporal patterns, while HMM helped uncover latent weather regimes. These models offer valuable insights for optimizing energy systems under changing environmental conditions.
