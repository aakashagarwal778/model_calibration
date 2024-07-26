# Calibration of the Heston Stochastic Volatility Model

## Project Overview

This project involves calibrating the Heston stochastic volatility model for European call options on the S&P 500 index. The objective is to estimate the model parameters by fitting it to real market data, achieving minimal error between observed option prices and those predicted by the model.

## Key Achievements

- **Parameter Estimation**: Accurately estimated the Heston model parameters by optimizing the model fit to actual market data.
- **Data Visualization**: Validated calibration accuracy by comparing the fitted model prices with observed market prices through visualization.

## Implementation

### Calibration Process

1. **Data Handling**:
   - Utilized a dataset (`option_prices_sp500.csv`) containing market data for European call options, including strike prices, option prices, and other relevant parameters.

2. **Optimization**:
   - The model parameters were estimated by minimizing the mean squared error between observed option prices and those predicted by the Heston model.
   - Optimization was performed with constraints to ensure realistic parameter values.

3. **Model Fitting**:
   - Used the Heston model to compute theoretical option prices based on the fitted parameters.

4. **Visualization**:
   - Plotted the fitted model prices against the observed market prices to assess calibration performance.

## Installation and Setup

1. Clone the Repository:

   ```bash
   git clone https://github.com/aakashagrawal778/model_calibration.git
   cd model_calibration

2. **Install Dependencies**:

   Ensure you have the required Python packages. Install them using pip:

   ```bash
   pip install numpy scipy matplotlib


3. **Run the Calibration:**
   Execute the Python script to perform the calibration and generate the plot. Replace your_script_name.py with the name of your Python script:

   ```bash
   Copy code
   python your_script_name.py

## Acknowledgements
Implemented based on standard financial and numerical methods for stochastic volatility models.


