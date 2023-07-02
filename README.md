# PJM Hourly Energy Consumption Forecasting

This project focuses on forecasting hourly energy consumption in the PJM Interconnection region. The PJM Interconnection LLC is a regional transmission organization operating an electric transmission system across several states in the United States.

## Dataset

The dataset used in this project is the [PJM Hourly Energy Consumption Data](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption). The data is sourced from Kaggle and consists of hourly power consumption measurements in megawatts (MW).

## Forecasting Method

For this project, XGBoost, a popular machine learning algorithm, was employed for time series forecasting. XGBoost is known for its ability to handle complex relationships and capture non-linear patterns in the data.

## Repository Contents

The repository contains the following files:

- `time_series.ipynb`: Jupyter Notebook containing the data preprocessing, model training, and forecasting steps.
- `PJM_Load_hourly.csv`: Dataset file containing the hourly energy consumption data.
- `README.md`: This file, providing an overview of the project.

## Usage

To reproduce the forecasting results, follow these steps:

1. Install the required dependencies listed in the `requirements.txt` file.
2. Run the `time_series.ipynb` notebook in a Jupyter environment.
3. The notebook will guide you through the data preprocessing, model training, and forecasting process.

## Additional Information

Please note that this project focuses on a specific region and time period. The dataset may not cover all regions or time periods within the PJM Interconnection. It is recommended to refer to the official PJM website for more comprehensive and up-to-date information.

For more details about the dataset and forecasting methodology, please refer to the notebook and comments within the code.


 
