# Nvidia-Stock-Prediction
A simple linear regression model to predict NVIDIA stock prices based on historical data.

# NVIDIA (NVDA) Stock Price Prediction

A simple stock price prediction model using Linear Regression to forecast NVIDIA's stock price based on the last year of historical data.

## Project Description

This project is an educational exercise in machine learning for finance. It fetches one year of historical stock data for NVIDIA (ticker: NVDA) from the yfinance package, preprocesses the data, and trains a basic Linear Regression model to predict the next day's closing price.

## Features

-   Fetches historical stock data using the `yfinance` library.
-   Preprocesses and prepares data for model training.
-   Trains a Linear Regression model using `scikit-learn`.
-   Visualizes the actual vs. predicted stock prices using `matplotlib`.

## Technologies Used

-   **Python**
-   **Pandas:** For data manipulation and analysis.
-   **Scikit-learn:** For building the Linear Regression model.
-   **yfinance:** To download market data from Yahoo! Finance.
-   **Matplotlib:** For data visualization.
-   **Jupyter Notebook**

## Setup and Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Nitant-Suhagiya/Nvidia-Stock-Prediction.git
    cd Nvidia-Stock-Prediction
    ```

2.  **Install the required libraries:**
    ```bash
    pip install pandas scikit-learn yfinance matplotlib
    ```

3.  **Run the model:**
    Open the Jupyter Notebook (`stock_prediction.ipynb`).
    ```bash
    python predict.py
    ```

## Disclaimer

**This project is for educational purposes only and should not be used as financial advice.** Stock market prediction is inherently complex and volatile. The linear regression model used here is too simple for real-world trading decisions.
