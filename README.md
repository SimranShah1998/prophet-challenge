# Forecasting Net Traffic with Prophet: Mercado Libre Growth Analysis

## Description

This project analyzes Mercado Libre's Google search trends, stock price patterns, and seasonal traffic data to determine if search traffic can predict stock trading behavior. The assignment utilizes data visualization, statistical analysis, and Prophet for time series modeling to uncover insights about user behavior and its relationship with the company’s stock performance.

## Files Included

- forecasting_net_prophet.ipynb: The main Google Colab notebook containing the analysis, code, and visualizations.

- completed assignment for Prophet Challenge: Completed assignment
  
- README.md: This file, providing an overview of the project and instructions.

## Technologies Used

- Programming Language: Python

### Libraries:

- Pandas

- Matplotlib

- NumPy

- Prophet

### Platform: 

- Google Colab
  

## Assignment Steps

### Step 1: 

Find Unusual Patterns in Google Search Traffic

Goal: Identify unusual search trends and their relationship to corporate financial events.

Key Actions:

- Filtered and analyzed search data for May 2020 (quarterly financial results release).

- Compared total search traffic in May 2020 to the monthly median across all months.

- Conclusion: Google search traffic increased significantly during this month.

### Step 2: 

Mine the Data for Seasonality

Goal: Identify seasonal patterns in search traffic.

Key Actions:

- Analyzed traffic by hour, day of the week, and week of the year.

- Observed hourly peaks (8 PM – 9 PM) and weekly trends (higher traffic on weekends).

- Identified increased activity during later weeks of the year.

### Step 3: Relate Search Traffic to Stock Prices

Goal: Explore correlations between search traffic and stock performance.

Key Actions:

- Merged search and stock price data into a single DataFrame.

- Analyzed trends during the first half of 2020 (January to June).

- Created features like "Lagged Search Trends," "Stock Volatility," and "Hourly Stock Return."

### Conclusion: 

No strong predictive relationship was observed between search traffic and stock metrics.

### Step 4: 

Create a Time Series Model with Prophet

Goal: Build a forecast model to predict future search traffic trends.

Key Actions:

- Set up a time series model using Prophet.

- Visualized search traffic forecasts and identified key seasonal components.

## Insights:

- Peak popularity occurs in the evening.
  
- Weekends exhibit the highest search traffic.

- Lowest traffic is observed mid-year.

### Results and Insights

- Google search traffic shows clear seasonal trends by time of day, day of the week, and week of the year.

- No strong correlation exists between search traffic and stock performance or volatility.

- The Prophet model accurately forecasts future search trends, helping predict peak times for user engagement.
