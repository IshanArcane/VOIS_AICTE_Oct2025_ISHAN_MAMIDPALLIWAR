# Project : Airbnb Hotel Booking Analysis (NYC) 🏨

## Problem Statement

Analyze the New York City Airbnb dataset to extract actionable insights into the city’s dynamic lodging market. This project aims to identify factors influencing listing availability, pricing strategies, and host performance.

## Key Analysis & Insights

- **Data Quality & Cleaning:**  
  Extensive cleaning was performed, including handling missing data, converting columns (e.g., last review to datetime), correcting typographical errors (such as ‘brookln’ to ‘Brooklyn’), and managing outliers in the availability_365 column.
- **Geographical Concentration:**  
  Manhattan was found to contain the highest number of listings among all neighborhood groups.
- **Pricing Structure:**  
  Discovered a strong positive correlation (≈1.0) between a listing’s base price and its service fee, indicating the fee is directly dependent on the price.
- **Host Performance:**  
  The number of listings a host owns (calculated host listings count) shows a very weak relationship (≈0.07) with their properties’ yearly availability.
- **Host Quality:**  
  Explored the relationship between host identity verification and average review rate.

## Deliverables

- Bar charts visualizing neighborhood and property type distributions.
- Regression plots illustrating correlations between pricing and availability factors.
- Data validation checks demonstrating improved data reliability after cleaning.

## Technology Stack

| Category          | Tool / Library                  | Purpose                                     |
|-------------------|---------------------------------|---------------------------------------------|
| Language          | Python                          | Core programming language for all analysis  |
| Environment       | Google Colab                    | Cloud-based execution environment           |
| Data Manipulation | Pandas                          | Data cleaning, aggregation, transformation  |
| Numerical         | NumPy                           | Fundamental array operations                |
| Visualization     | Matplotlib, Seaborn, Plotly     | Static & interactive plots (bar, line, regression) |

## How to Run the Project

1. Clone this repository to your local machine.
2. Open the Google Colab or Jupyter notebooks containing the project code.
3. Ensure the required datasets (e.g., `netflix_titles.csv`, `Airbnb_NYC.csv`) are available in the correct path or uploaded to your environment.
4. Execute the notebook cells sequentially to reproduce the analysis and visualizations.
