# Automate API Extraction and Data Analysis
 ## Project Overview
This project is designed to automate the process of extracting data from the CoinMarketCap API, normalizing it into a structured format, appending new data, and performing data analysis with visualizations. The primary focus is on cryptocurrency data.

# Features
* API Request Setup: Connects to the CoinMarketCap API to fetch the latest cryptocurrency listings.
* Data Extraction: Processes the API response to extract relevant data.
* Data Normalization: Converts the JSON response into a pandas DataFrame for easy manipulation and analysis.
* Timestamp Addition: Adds a timestamp to each record for tracking the data over time.
* API Runner Function: Repeatedly fetches and appends data to build a comprehensive dataset.
* Data Visualization: Uses seaborn and matplotlib to create visual representations of the data.
* Data Filtering: Filters data for specific cryptocurrencies to focus on targeted analysis.
* Plotting: Plots the filtered data for visual insights.
