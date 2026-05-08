# Time Series Forecasting — Air Passengers Dataset

## Overview

This repository presents a complete workflow for univariate time series forecasting using the Air Passengers dataset. The project compares classical statistical methods, machine learning models, and deep learning architectures for passenger demand forecasting.

The notebook includes:

- Exploratory Data Analysis (EDA)
- Stationarity analysis
- Seasonal decomposition
- Forecast evaluation metrics
- Classical forecasting models
- Machine learning forecasting models
- Deep learning forecasting models
- Visual comparison of predictions
- Model selection guidelines

## Dataset

Dataset: `air_passengers.csv`

The dataset contains monthly airline passenger totals over time.

## Project Structure

```text
.
├── Time_Series_Forecasting_AirPassengers.ipynb
├── air_passengers.csv
└── README.md
```

## Models Included

### Classical Statistical Models

- ARIMA
- SARIMA
- Simple Exponential Smoothing
- Holt-Winters Exponential Smoothing
- Prophet

### Machine Learning Models

- LightGBM
- Gradient Boosting
- XGBoost

### Deep Learning Models

- Simple RNN
- LSTM

## Requirements

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels prophet lightgbm xgboost tensorflow torch
```

## How to Reproduce the Results

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Create a Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels prophet lightgbm xgboost tensorflow torch
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Time_Series_Forecasting_AirPassengers.ipynb
```

### 5. Run the Notebook Sequentially

Execute all notebook cells from top to bottom to:

1. Load and preprocess the dataset
2. Perform exploratory data analysis
3. Analyze stationarity and seasonality
4. Train forecasting models
5. Generate predictions
6. Compare model performance
7. Visualize forecasting results

## Evaluation Metrics

The models are evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)

## Results

The notebook compares forecasting accuracy across multiple approaches and highlights the strengths and limitations of each model family for time series forecasting.

## Author

Manuel Eugenio Morocho Cayamcela, PhD
