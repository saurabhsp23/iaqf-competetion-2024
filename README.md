# IAQF 2024 

This project conducts an in-depth analysis of Market-Based Probability Densities (MPDs) to
forecast financial market trends, particularly focusing on volatility and market reversals. We
employ a comprehensive dual-method approach, integrating both unconditional and
conditional assessments, to evaluate MPDs' enhancement of time-series models and their
application in empirical trading strategies. Our investigation covers two primary strategies: a
multi-factor trading strategy that combines advanced machine learning with traditional
statistical models, and a pair trading strategy that leverages MPD data for market exposure
mitigation and efficacy enhancement. Preliminary results reveal the variable effectiveness of
MPDs across different asset classes, demonstrating their potential to navigate complex market
dynamics and improve investment outcomes when appropriately integrated into trading
strategies.

# Project Structure

This project analyzes financial datasets using a rolling window approach and statistical techniques. The notebook includes helper functions, data preprocessing, and optimization methods.

## Overview
The project performs the following key tasks:
1. Fetching and preprocessing financial data.
2. Statistical analysis using tools like ADFuller and rolling z-scores.
3. Implementation of rolling window techniques.
4. Optimization using `optuna`.
5. Visualization with `matplotlib` and `seaborn`.

## Notebook Structure

### Sections
1. **Imports and Setup**: Necessary libraries like `pandas`, `matplotlib`, `statsmodels`, and `optuna` are imported and configured.
2. **Helper Functions**: Functions for data fetching, spread calculation, and rolling window operations.
3. **Statistical Analysis**: Tools for testing stationarity and calculating rolling metrics.
4. **Optimization**: `optuna` used for hyperparameter tuning.
5. **Visualizations**: Insights are displayed using plots and charts.

### Key Functions and Processes
- **Rolling Window Calculations**: Analyze trends over specific periods.
- **Statistical Tests**: Perform ADFuller and z-score analysis.
- **Data Visualization**: Generate visual representations of trends.
- **Optimization Framework**: Optimize parameters for statistical models.

## Example Usage
1. Clone the repository.
2. Install dependencies using `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute the Jupyter notebook in the `notebooks/` directory to reproduce the analysis.

