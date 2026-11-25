# Multi-Horizon Electricity Consumption Forecasting System

> **Note:** The active codebase, trained models, smart-meter datasets, and full benchmarking suite for this research project are maintained and actively developed at [**Chaitanya-cpu287/VoltCast**](https://github.com/Chaitanya-cpu287/VoltCast).

---

## Overview

This repository archives the foundational research and specifications for multi-horizon electricity consumption forecasting using smart-meter telemetry data.

The project models multi-step forward demand profiles across residential and commercial feeders, allowing grid operators to anticipate load variations, schedule dispatch efficiently, and minimize transmission inefficiencies.

### Core Architecture & Implementation Highlights (VoltCast)

- **Telemetry Data Ingestion:** Real-world smart meter time-series datasets from Mathura feeder networks.
- **Feature Engineering:** Cyclic time encodings (hour of day, day of week, seasonal shifts), rolling window aggregations, and multi-step lag features.
- **Model Ensembles:** Gradient boosted decision trees (XGBoost, LightGBM) and Random Forest regressors compared against baseline autoregressive models.
- **Evaluation Metrics:** Multi-horizon RMSE, MAE, and R² scores.

For source code, setup instructions, and evaluation scripts, please visit:
👉 **[https://github.com/Chaitanya-cpu287/VoltCast](https://github.com/Chaitanya-cpu287/VoltCast)**
