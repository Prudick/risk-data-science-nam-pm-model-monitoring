# NAM Portfolio Model Monitoring

## Overview
This repository contains the monitoring framework for the NAM Portfolio Model, which was developed by BCG using LightGBM Binary Classification. The target variable is **60 Days Past Due (60DPD) in the next 12 months**. The model was developed in **April 2023** and has been in production since **June 2023**, with predictions made on a batch basis.

## Model Details
- **Model Type**: LightGBM Binary Classification
- **Target Variable**: 60DPD in the next 12 months
- **Developed By**: BCG
- **Development Date**: April 2023
- **Production Date**: June 2023
- **Deployment Type**: Batch prediction

## Why Monitor?
Continuous monitoring is essential to ensure that the model remains reliable, accurate, and effective in a changing environment. The monitoring framework:
- Detects and escalates emerging issues early.
- Evaluates the model's performance over time to maintain confidence in its outputs.
- Monitors key performance metrics and indicators, including:
  - **Model performance**: Accuracy, precision, recall, and F1-score.
  - **Data drift**: Changes in data patterns that could affect model predictions.
  - **Model drift**: Changes in the model's performance over time.
  - **Anomalies**: Unusual patterns in predictions or input data.

## Monitoring Approach
The monitoring framework is designed to:
- **Track model performance**: Ensures that the model outputs align with expected performance benchmarks.
- **Identify and address data drift**: Detects shifts in input data distribution, which may impact the model’s predictions.
- **Manage deviations and anomalies**: Provides alerts for significant deviations from expected behavior, allowing for quick interventions.

## Key Features
- **Dynamic and responsive**: Adapts to the model's evolving environment.
- **Escalation mechanisms**: Automatically triggers alerts when performance thresholds are breached.
- **Customizable**: Tailored specifically to suit the NAM Portfolio Model’s characteristics and its application domain.

## How to Use
1. Clone the repository: 
   ```bash
   git clone https://github.com/Prudick/risk-data-science-nam-pm-model-monitoring.git