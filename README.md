# Time-Series Analysis & Forecasting with Python 📈📉📊⏰

Welcome! I’m **Mustafa Alsaegh**, and this repo is my end-to-end toolkit for **time-series analysis and forecasting** in Python. It’s built for fast learning and real projects—from quick EDA and visualization to classical stats models, deep learning, and Prophet-style forecasting.

Whether you’re just getting started or you want a solid reference for production-ready workflows, you’ll find something useful here. 🤘

---

## Contents 📄

- **[Datasets Info](./Datasets_Info.md) 📋**
  - Brief notes on each dataset and how I use them in notebooks.

- **[Introduction to Time Series Analysis (Theory)](./Introduction_TSA.md) 🕰**
  - What “time series” really means
  - Best practices for picking models
  - Classic baselines you should always try
  - Turning time series into supervised learning problems
  - When and why to use deep learning

- **[Time Series Data Visualization](./Time_Series_Data_Visualization_Basics.ipynb) 📉**
  - Plotting with pandas
  - Titles, axis labels, styles, and colors
  - Slicing by date; tick spacing & date formatting
  - Major/minor ticks and gridlines

- **[Time Series EDA](./Time_Series_Data_EDA.ipynb) 📊**
  - Resampling, down/upsampling
  - Time shifting (lead/lag)
  - Rolling and expanding windows
  - Cumulative stats for stability checks

- **[Time Series Data Analysis](./Time_Series_Data_Analysis.ipynb) 💹**
  - `statsmodels` basics
  - Hodrick–Prescott filter (trend/cycle)
  - Stationarity & ADF test
  - Granger causality
  - Decomposition (additive/multiplicative)
  - Moving average & EWMA (single/double)
  - Holt–Winters (triple exponential smoothing)

- **[Forecasting — Classical Methods](./Time_Series_Forecasting_Traditional_Methods.ipynb) 🤖**
  - ACF / PACF / autocovariance
  - AR(p), ARMA, ARIMA
  - ETS decomposition
  - SARIMA & SARIMAX (with exogenous variables)
  - Holt–Winters seasonal variants

- **Forecasting — Deep Learning 🕸️**
  - [MLPs for forecasting](./Time_Series_Forecasting_With_MLPs.ipynb)
  - [LSTMs for forecasting](./Time_Series_Forecasting_With_LSTMs.ipynb)
  - (Optional) CNNs & Transformers — add-on notebooks as I publish updates

- **Forecasting with Prophet 🎯**
  - [Univariate & Multivariate with Prophet](./Time_Series_Forecasting_With_Prophet.ipynb)

- **(Bonus) Lightweight AutoML for TS 🦾**
  - Automating model search with FLAML *(coming as an optional notebook here)*

---

## What you’ll learn (quick hits)

- How to structure time-series projects so you don’t get stuck later.
- Reliable baselines (ARIMA/Holt-Winters) before jumping to deep nets.
- Feature engineering patterns (lags, rolling stats, calendar flags).
- When LSTM/MLP/CNN/Prophet make sense—and when they don’t.
- Practical plotting + diagnostics that save hours of guesswork.

---

## Getting started

1. Create an environment (conda or venv) and install common libs:
   ```bash
   conda create -n ts python=3.10 -y
   conda activate ts
   pip install numpy pandas matplotlib statsmodels pmdarima scikit-learn prophet
   # deep learning extras if you want:
   pip install torch tensorflow  # pick one stack for the DL notebooks
