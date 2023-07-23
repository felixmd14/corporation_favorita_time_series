# **Regression Project for Time Series Forecasting of Store Sales for Corporation Favorita**

This is a regression project for time series forecasting of store sales for Corporation Favorita, a large retail corporation with stores throughout Latin America. The project uses data from 2013 to 2017 and includes information on daily sales, promotions, and weather patterns, among other variables. The goal of the project is to develop a regression model that can accurately forecast store sales for the next year, based on historical data.

## Data
The data used in this project is available in the following files:

- **holidays_events.csv:** Details about the holidays and events that occurred during the given period.
- **oil.csv:** Daily oil price data.
- **sample_submission.csv:** Sample submission file in the correct format for the competition.
- **stores.csv:** Details about the stores in the given period.
- **test.csv:** Test dataset containing store-item pairs for the forecasting period.
- **train.csv:** Training dataset containing store-item pairs for the given period.
- **transactions.csv:** Daily transactions data for all stores.
The **train.csv** and **test.csv** files are the main datasets for the regression project.

### Approach
The regression model for time series forecasting of store sales is developed using the following approach:

1. **Data exploration:** Explore the data to gain insights into the underlying patterns and trends, and identify any outliers or anomalies that may need to be addressed before training the model.

2. **Feature engineering:** Engineer relevant features from the data, such as lagged variables, moving averages, and seasonal factors.

3. **Model selection:** Select an appropriate regression technique, such as autoregressive integrated moving average (ARIMA), that can capture the temporal dependencies and trends in the data.

4. **Model training:** Train the regression model on the data from 2013 to 2016.

5. **Model validation:** Validate the regression model on the data from 2017 and evaluate its accuracy using statistical measures such as mean absolute error (MAE) and mean squared error (MSE).

6. **Forecasting:** Use the trained regression model to forecast store sales for the next year, based on historical data.

### Requirements
This project requires the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `statsmodels`

### Usage
1. Clone this repository:

`git clone https://github.com/yourusername/regression-project-store-sales.git`

`cd regression-project-store-sales`

2.Install the required libraries:

`pip install -r requirements.txt`

3. Run the sales_forecasting.ipynb notebook:

jupyter notebook `sales_forecasting.ipynb`

4. Follow the instructions in the notebook to explore the data, train the regression model, validate the model, and forecast future sales.

## Conclusion
This regression project for time series forecasting of store sales for Corporation Favorita can help the company make more informed decisions about inventory management, staffing, and marketing. By analyzing historical data and identifying relevant patterns and trends, we can develop a regression model that accurately forecasts store sales for the next year. This can help the company optimize its operations and improve its bottom line.
