# Spotify Popularity Analysis

## Project Overview
This project explores the relationship between Spotify audio features and song popularity. 
Through exploratory data analysis, feature transformation, segmentation, and regression modeling, the study evaluates how acoustic characteristics influence streaming performance.

Due to file size limitations, a representative sample of the dataset (5,000 observations) is included.


## Objectives
- Analyze relationships between energy, duration, and popularity.
- Segment songs using quantile-based thresholds.
- Standardize variables for fair comparison.
- Build a regression model to predict popularity.

## Exploratory Data Analysis (EDA)
- Correlation matrix between acoustic features.
- Energy-based segmentation (Q1 vs Q3 comparison).
- Fixed threshold comparison (Energy > 0.6 vs ≤ 0.6).
- Duration categorization (Short, Medium, Long, Very Long).
- Scatter analysis of duration vs energy colored by popularity.

## Data Transformation
- Duration converted from milliseconds to minutes.
- Duration categorized into 4 groups.
- Popularity scaled for fair comparison.
- Numerical standardization applied where necessary.

## Predictive Modeling
A Linear Regression model was built using:

- energy
- duration_min
- loudness
- danceability
- valence
- speechiness
- liveness
- instrumentalness
- acousticness

### Model Performance:
- R²: 0.35  
- MSE: 318.89  

The model explains 35% of the variance in popularity, indicating moderate predictive power.

## Business Implications
- High-energy songs show significantly higher average popularity.
- Duration alone is not a strong predictor.
- Acoustic combinations matter more than individual features.
- Data-driven segmentation can support music marketing strategies.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Google Colab

## Author
Paula Vanesa Criollo Nuñez  
Industrial Engineer | Data Analysis Enthusiast
