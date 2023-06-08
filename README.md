# Project Overview

This project provides a Python Jupyter Notebook to analyze and visualize customer cohorts in the form of a heatmap. The heatmap displays the total number of orders for each cohort week and bucket, giving insights into customer behavior and order patterns.

The code reads a dataset containing information about customer orders, calculates the total number of customers per cohort, and the percentage of first-time orders per cohort. It then generates a heatmap to visualize the total orders metrics.

## How to Run

1. Make sure you have Python 3.3+ installed on your system.
2. Install the required libraries:

pip install pandas matplotlib seaborn

3. Ensure you have the path to the orders.csv and the customers.csv. It will be easiest if you place the files in the same directory as the code. 
4. Also refer to the following list of compatible US timezones to be passed into the code: 
    America/New_York
    America/Detroit
    America/Kentucky/Louisville
    America/Kentucky/Monticello
    America/Indiana/Indianapolis
    America/Indiana/Vincennes
    America/Indiana/Winamac
    America/Indiana/Marengo
    America/Indiana/Petersburg
    America/Indiana/Vevay
    America/Chicago
    America/Indiana/Tell_City
    America/Indiana/Knox
    America/Menominee
    America/North_Dakota/Center
    America/North_Dakota/New_Salem
    America/North_Dakota/Beulah
    America/Denver
    America/Boise
    America/Phoenix
    America/Los_Angeles
    America/Anchorage
    America/Juneau
    America/Sitka
    America/Metlakatla
    America/Yakutat
    America/Nome
    America/Adak
    Pacific/Honolulu

5. Run the Jupyter notebook cell by cell. The first couple of cells require input, so DO NOT hit "RUN ALL"

## Outputs 
1. The notebook will output a heatmap and save it as a high-quality PNG file named `total_orders_cohort_analysis.png` in the same directory as the script.
2. It will also output a csv file with cohort week data, day range, and percentages for total orders and first time orders. 

## Drawbacks

- The current implementation assumes that the dataset has specific column names and formats. This may require manual adjustments for different datasets.
- The heatmap visualization is static and may not be suitable for real-time or interactive analysis.

## Future Functionality

- Add support for custom column names and formats to improve flexibility and compatibility with various datasets.
- Implement an interactive heatmap visualization using a web-based framework (e.g., D3.js, Plotly) for better user experience and real-time analysis capabilities.
- Include additional cohort metrics and customization options for the heatmap visualization.
- Write tests for each of the functions to ensure functionality.


### Written by Preet Kaur for Invitae
