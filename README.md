## Overview
This project focuses on **time series forecasting** for energy consumption using two different deep learning models:

- **PatchTST**: A Transformer-based model that applies patching and channel independence for time series tasks.
- **DLinear**: A linear decomposition model that separates time series into trend and seasonal components for efficient forecasting.

The study compares the **accuracy, computational efficiency, and scalability** of these models across **hourly and daily energy consumption datasets**.

## Objectives
- Preprocess and explore the energy consumption dataset.
- Train and evaluate **PatchTST** and **DLinear** on both hourly and daily frequency data.
- Compare performance using metrics such as:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Percentage Error (MAPE)
- Analyze strengths and weaknesses of each model.
