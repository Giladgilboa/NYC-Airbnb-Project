# NYC Airbnb Price Analysis

This project analyzes Airbnb listing prices across New York City, focusing on neighborhood comparisons, cost-effectiveness, and key factors influencing rental prices. The analysis uses R for data manipulation, visualization, and statistical analysis.

## Project Overview

The main goals of this project include:
- **Neighborhood Price Comparison**: A heatmap showing average Airbnb prices across different NYC neighborhoods.
- **Cost-Effective Listings**: An algorithm to identify the top 1000 most cost-effective Airbnb listings.
- **Price Distribution**: Comparison of price distributions between neighborhoods.
- **Bootstrapping**: A statistical method to estimate the average price of Airbnb listings with confidence intervals.
- **Correlation Study**: Examining correlations between price and other factors like number of reviews, ratings, and availability.

## Data Sources

- **Airbnb Open Data**: The dataset includes listings of Airbnb properties in New York City.
- **GeoJSON File**: Used to map neighborhood boundaries and visualize the data geographically.
- **CSV Data**: A structured dataset used for analysis.

## Key Features

- **Neighborhood Price Heatmap**: Visual representation of average prices across NYC neighborhoods.
- **Top 1000 Cost-Effective Listings**: Ranked based on factors such as price, host verification, booking flexibility, and user ratings.
- **Correlation Analysis**: Study of the relationship between price and various listing attributes.
- **Bootstrapping Analysis**: Resampling method to estimate average prices and their confidence intervals.

## Technologies Used

- **R**: Data manipulation, visualization, and statistical analysis.
- **Leaflet**: For interactive map visualizations.
- **ggplot2**: For data visualizations.
- **dplyr**: For data wrangling.
- **GeoJSON**: For geographic data visualization.
