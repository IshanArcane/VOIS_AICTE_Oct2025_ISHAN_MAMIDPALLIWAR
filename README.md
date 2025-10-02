Data Science Portfolio: Content & Hospitality Analytics

This repository showcases two distinct data analysis projects built using the Python data science stack, focusing on strategic insights for the streaming entertainment and hospitality industries.
1. Project A: Netflix Content Trends Analysis 🎬
Problem Statement

To perform a Content Trends Analysis for Strategic Recommendations by uncovering how Netflix’s content distribution (Movies vs. TV Shows, genres, and country contributions) has evolved from 2008–2021. The goal is to identify strategic strengths, gaps, and opportunities for content acquisition and production.
Objectives

    Analyze the distribution and evolution of Movies vs. TV Shows over the years.

    Identify the most common genres and analyze how their popularity has changed over time.

    Compare country-wise contributions to Netflix’s content catalog.

Key Findings

    Content Pivot: Analysis revealed a decisive and continuous upward trend in TV Show acquisition in recent years, signaling a strategic shift to satisfy growing demand for serial content.

    Geographical Focus: Content contribution is heavily concentrated in the United States, India, and the United Kingdom, highlighting key markets for localized content investment.

    Genre Concentration: Dramas and International Movies remain primary categories, though specific emerging genres were identified as targets for future diversification.

    Talent Impact: Data was processed to identify the top 10 directors and cast members by volume of content contributed to the platform.

Deliverables

    Interactive line plots showing content (Movie/TV Show) acquisition trends over time.

    Geographical bar charts highlighting major content contributors.

    Strategic recommendations document for content planning executives.

2. Project B: Airbnb Hotel Booking Analysis (NYC) 🏨
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
