Project : Airbnb Hotel Booking Analysis (NYC) 🏨
Problem Statement

To analyze the New York City Airbnb dataset to extract meaningful insights into the city's dynamic lodging market by discerning factors influencing listing availability, pricing strategies, and host performance.
Key Analysis & Insights

    Data Quality & Cleaning: Extensive cleaning involved handling missing data, converting data types (e.g., last review to datetime), and correcting typographical errors (e.g., 'brookln' to 'Brooklyn'). Outliers in the availability 365 column were also managed.

    Geographical Concentration: Identified that the Manhattan neighborhood group holds the highest number of listings.

    Pricing Structure: Discovered an extremely strong positive correlation (≈1.0) between a listing's base price and its service fee, suggesting the fee is directly dependent on the price.

    Host Performance: Found that the number of listings a host owns (calculated host listings count) has a very weak relationship (≈0.07) with their properties’ yearly availability.

    Host Quality: Analyzed the relationship between host identity verification and the average review rate.

Deliverables

    Bar charts visualizing neighborhood and property type distribution.

    Regression plots illustrating correlations between pricing and availability factors.

    Data validation checks demonstrating data reliability after cleaning.

Technology Stack

Category
	

Tool / Library
	

Purpose

Language
	

Python
	

Core programming language for both projects.

Environment
	

Google Colab
	

Cloud-based execution environment.

Data Manipulation
	

Pandas
	

Handling large datasets, cleaning, aggregation (groupby, explode).

Numerical Computing
	

NumPy
	

Fundamental support for array operations.

Visualization
	

Matplotlib, Seaborn, Plotly Express
	

Generating static and interactive plots (bar charts, line trends, regression plots).
How to Run the Project

    Clone this repository to your local machine.

    Open the Google Colab notebooks (or Jupyter notebooks) containing the project code.

    Ensure the required datasets (netflix_titles.csv, Airbnb_NYC.csv - assuming similar files were used for the Airbnb analysis) are placed in the correct path or uploaded to your environment.

    Execute cells sequentially.
