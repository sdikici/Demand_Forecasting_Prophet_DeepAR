# Electricity Demand Forecasting with DeepAR and Prophet
This repository contains Python code for evaluating Amazon DeepAR and Meta Prophet models for electricity demand forecasting. The methodology employed in this research is outlined below, detailing the steps taken to collect data, prepare it for analysis, develop models, and assess their performance.

- Methodology Overview
The methodology follows a structured approach, as illustrated in Figure 17, to conduct a comprehensive analysis of load forecasting. Here's a brief overview of each step:

Data Collection: Two datasets are compiled—one for electricity consumption and another for weather patterns. The electricity dataset includes a binary column indicating holidays.

Data Preparation and Processing: After cleaning and feature selection, the datasets are merged, creating three datasets: one for energy consumption, one for holidays as regressors, and one comprehensive dataset including weather data.

Model Development: DeepAR and Prophet models are developed in Python and trained on the three datasets for various forecast horizons (7, 15, 30, and 90 days). The models are evaluated using metrics such as MAPE, RMSE, and R-squared.

Model Evaluation: The evaluation results are tabulated to compare the performance of DeepAR and Prophet models across different forecast horizons.

Model Selection: Based on evaluation metrics and training/testing speed, the most appropriate model is selected for further analysis and deployment.

Prototype Creation: The selected model is prepared for deployment, ensuring the codebase is optimized and meets performance standards.

- Conclusion
The methodology outlined here provides a systematic approach to evaluating DeepAR and Prophet models for electricity demand forecasting. By comparing their performance across various metrics, we aim to select the most accurate and efficient model for real-world deployment. The repository contains the necessary code and data to replicate and extend this research.
