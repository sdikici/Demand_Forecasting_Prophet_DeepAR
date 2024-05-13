# Electricity Load Forecasting with Prophet
This project implements a forecasting model using the Prophet library to predict electricity demand based on historical time series data. The model incorporates various factors such as temperature and holidays to improve prediction accuracy.

- Overview
The forecasting model is built using the Prophet library in Python, which is developed by Facebook's Core Data Science team. Prophet is designed for forecasting time series data and is particularly adept at handling datasets with multiple seasonalities and missing data.

- Usage
The main script (main.py) contains the function predict_and_evaluate, which takes the following inputs:

csv_file: Path to the CSV file containing the time series data.
days_to_predict: Number of days to forecast into the future.
freq: Frequency of the data (e.g., "2H" for 2 hourly).
country_name: Country code for holiday consideration (e.g., "UK" or "DE").
The function returns evaluation metrics and a plot of the forecasted values.

- Example

predict_and_evaluate("data/merged_data.csv", 30, "2H", "UK")

- Interface
The project includes a Gradio interface for easy interaction. Upload your CSV file, specify the number of days to predict, data frequency, and country code, then click "Launch" to see the forecasted results.

- Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

-License
This project is licensed under the MIT License - see the LICENSE file for details.
