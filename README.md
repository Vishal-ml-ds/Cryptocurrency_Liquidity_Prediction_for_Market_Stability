## Overview

This project is a machine learning pipeline designed to predict the liquidity of cryptocurrencies using historical market data. The primary goal is to identify early signs of liquidity crises, which can lead to market instability. By forecasting a custom liquidity ratio based on features like price, volume, and market cap, the model provides insights that can help traders and financial institutions manage risk more effectively.

The project includes data preprocessing, feature engineering, model training, and a simple web application for real-time predictions.

## Features

- **Data Preprocessing:** Cleans and normalizes raw market data from CoinGecko.
- **Feature Engineering:** Creates insightful features, including a 3-day price moving average and a custom liquidity ratio.
- **Predictive Modeling:** Utilizes a Random Forest Regressor to predict the liquidity ratio.
- **Interactive Web App:** A user-friendly interface built with Streamlit to serve real-time predictions from the trained model.

## Technology Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Matplotlib
- Seaborn


## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd <repository-directory>
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## How to Run

1.  **Run the ML Pipeline (Optional):**
    To process the data and retrain the model, run the main script.
    ```bash
    python main.py
    ```

2.  **Launch the Streamlit Web App:**
    To make predictions using the pre-trained model, launch the application.
    ```bash
    streamlit run app/app.py
    ```
   
