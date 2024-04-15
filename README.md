# prophet-challenge
Module 8 Challenge

## Overview
In this project, I analyze the hourly Google search traffic data for Mercado Libre, the largest e-commerce platform in Latin America. The goal is to uncover any unusual patterns in search traffic, mine the data for seasonality, relate the search traffic to stock price patterns, and finally, create a time series model with Prophet for forecasting.

## Data Sources
- Hourly Google search traffic data for Mercado Libre.
- Stock price data for Mercado Libre.

## Project Structure
- `prophet-challenge.ipynb`: Jupyter Notebook containing the Python code for the analysis.
- `data/`: Directory containing the raw data files.
- `plots/`: Directory containing plots generated during the analysis.

## Steps
1. **Find Unusual Patterns in Hourly Google Search Traffic**
   - Slice the data to May 2020 and visualize.
   - Compare total search traffic to monthly median.

2. **Mine the Search Traffic Data for Seasonality**
   - Analyze average traffic by hour of day, day of week, and week of year.

3. **Relate the Search Traffic to Stock Price Patterns**
   - Plot stock price data and concatenate with search traffic data.
   - Analyze common trends and relationships between search traffic and stock price.

4. **Create a Time Series Model with Prophet**
   - Set up the data for a Prophet forecasting model.
   - Plot forecast and analyze time series components.

## Results
- Found unusual patterns in search traffic during specific periods.
- Identified seasonality in search traffic by hour of day, day of week, and week of year.
- Observed correlations between search traffic and stock price patterns.

## Conclusion
The analysis provides insights into the relationship between Google search traffic for Mercado Libre and various financial and seasonal factors. These insights can be valuable for marketing strategies and investment decisions.
