# Google_PlayStore_analytics

## Google Play Store App Analysis: Uncovering Insights from App Data

This project analyzes Google Play Store app data using Python and Jupyter Notebooks to extract valuable insights into app ratings, categories, user reviews, pricing models, and installation trends. The goal is to understand the dynamics of the app market and identify key factors influencing app success.

## Project Overview

In today's mobile-first world, understanding the app market is crucial. This project analyzes a comprehensive dataset of Google Play Store apps using Python (with the Pandas library) within a Jupyter Notebook environment. We conduct a thorough exploratory data analysis (EDA) to uncover meaningful patterns and trends relevant to app developers, marketers, and anyone interested in the app landscape.

## Dataset

The analysis uses a CSV file named `googleplaystore.csv` ([lava18/google-play-store-apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)). This dataset contains the following attributes for each app:

*   `App`: Name of the app.
*   `Category`: Category the app belongs to.
*   `Rating`: App's rating on the Play Store.
*   `Reviews`: Number of user reviews.
*   `Size`: Size of the app.
*   `Installs`: Number of app installs.
*   `Type`: Whether the app is "Free" or "Paid".
*   `Price`: Price of the app.
*   `Content Rating`: Target audience for the app.
*   `Genres`: Genre(s) the app belongs to.
*   `Last Updated`: Date the app was last updated.
*   `Current Ver`: Current version of the app.
*   `Android Ver`: Minimum Android version required.

## Methodology

The analysis follows these steps:

1.  **Data Loading and Inspection:** Loading the dataset with Pandas and examining its structure, including data types, missing values, and memory usage.

2.  **Data Cleaning and Preprocessing:** Handling missing values and converting data types as needed (e.g., converting 'Installs' and 'Price' to numerical values).

3.  **Exploratory Data Analysis (EDA):** Answering specific questions through in-depth analysis:
    *   Basic descriptive statistics (mean, median, standard deviation, etc.)
    *   Analyzing app ratings and their distribution.
    *   Identifying top-performing app categories based on average rating.
    *   Investigating the relationship between reviews and app success.
    *   Comparing free and paid app performance.
    *   Analyzing installation trends.

4.  **Data Visualization:** Creating visualizations (Bar Chart for Avg Rating by Category, Pie Chart for Distibution of Free Vs Paid Apps, Bar chart for Top 10 Apps by Reviews)
