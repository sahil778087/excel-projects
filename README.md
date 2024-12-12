## Demand Forecasting Analysis and Dashboard

- This project is focused on analyzing and visualizing demand forecasting data to derive actionable business insights. 
The dataset includes various factors like price, discounts, weather conditions, and seasonality, which influence product demand.
The project also includes a dashboard design to present these insights in an interactive and user-friendly manner.

# Objectives

- Compare Forecasted Demand with Actual Performance:

- Assess the accuracy of demand forecasts.

- Identify and visualize variances between forecasted and actual sales.

- Analyze the Impact of External Factors on Demand:

- Understand relationships between demand and factors such as price, discount, weather, and category.

- Highlight category-specific insights to guide decision-making.

# Dashboard Development:

- Create dynamic and interactive Excel dashboards.

- Visualize key metrics such as forecast accuracy, inventory sufficiency, and revenue projections.

# Files in the Repository SYED_SAHIL_SHAFI(PROJECT2).xlsx:

The main dataset containing columns such as:

- Date: Time of the transaction.

- Price: Price of the product.

- Discount: Discount percentage applied.

- Units Sold: Actual sales data.

- Demand Forecast: Predicted demand for the product.

- Weather Condition: Weather during the period.

- Seasonality: Seasonal context (e.g., Summer, Winter).

- Category and Region: Product and regional information.

# Key Analyses and Visualizations

1. Compare Forecasted Demand with Actual Sales

Added columns for:

Forecast Accuracy (%): Measures how close the forecast is to actual sales.

Formula:

Accuracy (%) = (1 - ABS(Demand Forecast - Units Sold) / Demand Forecast) * 100

Absolute Error: Difference between forecasted and actual sales.

Visualized:

Line chart: Forecast vs. Actual Sales over time.

Bar chart: Forecast accuracy by category/region.

2. Impact of External Factors

Scatter Plots:

Price vs. Demand Forecast: Shows price sensitivity.

Discount vs. Units Sold: Visualizes the effect of promotions.

Bar Charts:

Demand by Weather Condition.

Category-specific demand variations.

3. Dashboard Components

KPIs:

Forecast Accuracy (%).

Total Absolute Error.

Average Units Sold.

Interactive Filters:

Slicers for Category, Region, and Seasonality.

Visual Elements:

Line charts, bar charts, and scatter plots.

How to Use

Open the dataset file (SYED_SAHIL_SHAFI(PROJECT2).xlsx) in Excel.

Follow the provided formulas and steps to perform the analyses:

Add calculated columns for forecast accuracy and absolute error.

Create pivot tables to summarize key metrics.

Insert scatter plots and trendlines to visualize relationships.

Use Excel's dashboard features (e.g., slicers, charts) to build an interactive view.

Insights

Forecast Accuracy: Identify categories or regions with high/low forecasting accuracy.

External Factors: Determine how discounts, pricing, and weather influence demand.

Inventory Optimization: Use demand forecasts to align inventory with expected demand.

Future Enhancements

Automate the forecasting process using machine learning models.

Develop a web-based dashboard for real-time analytics.

Include more external variables like competitor pricing and macroeconomic trends.
