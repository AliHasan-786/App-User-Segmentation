# App-User-Segmentation

## Overview
The project aims to analyze user engagement and spending in a mobile app, using data visualization to identify key patterns and user segments for better app management and marketing strategies.

## Dependencies
- Python
- Pandas
- Plotly
- Sklearn

## Data
The dataset (userbehaviour.csv) contains user-level data including:
- Average Screen Time
- Average Spending on App (INR)
- Review Left (Yes/No)
- User Ratings
- Password Reset Requests
- Last Visited Time
- User Status (Installed/Uninstalled)

## Preprocessing
- Data normalization using MinMaxScaler for clustering
- Handling missing values and outliers, if any
- Data is read and visualized to understand basic statistics like average, highest, and lowest screen time and spendings.
## Model Training and Evaluation
- K-means clustering is used to segment users into groups based on their behavior.
- The number of clusters is determined, and segments are labeled for clarity.
- Model evaluation involves analyzing cluster characteristics to ensure meaningful segmentation.
## Usage
- Load the dataset using Pandas.
- Perform exploratory data analysis to understand user behavior.
- Apply K-means clustering for user segmentation.
- Visualize results using Plotly to understand user segments.

## Results
- The analysis highlights the relationship between screen time, spending, and user retention.
- Three user segments are identified: Retained, Churn, and Needs Attention.
- Visualizations provide insights into the spending and engagement patterns of different user groups.
- Findings can be used to tailor strategies for user retention and targeted marketing.
