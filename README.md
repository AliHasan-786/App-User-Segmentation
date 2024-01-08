# App-User-Segmentation

## Overview
The project aims to analyze user engagement and spending in a mobile app, using data visualization to identify key patterns and user segments for better app management and marketing strategies.

## Dependencies
- Python
- Pandas
- Plotly

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
Data is read using Pandas. Basic statistical analysis is performed to understand average screen time and spending. No complex preprocessing is required.

## Model Training and Evaluation
- K-means clustering is used for user segmentation.
- Segments are identified based on screen time, spending, ratings, and other features.
- No traditional model training is involved, but clusters are evaluated based on their characteristics.

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
