# Google-PlayStore-EDA
Exploratory Data Analysis (EDA) of 2.3M+ Google Play Store apps, uncovering patterns in installs, ratings, categories, pricing, developer activity, and release trends.



Google Play Store EDA
A comprehensive Exploratory Data Analysis (EDA) of the Google Play Store Apps dataset covering 2.3M+ apps.
This project explores app categories, installs, ratings, reviews, pricing, developer activity, and release trends to uncover meaningful insights into the mobile app ecosystem.

Project Aim
The goal of this EDA is to:

Analyze app popularity through installs & user ratings
Explore category dominance & trends
Compare free vs. paid apps and pricing models
Study developer activity & publishing patterns
Understand release years & update frequencies
Workflow
Data Cleaning & Preparation

Standardized installs, ratings, app size & dates
Handled missing values & removed duplicates
Feature Engineering

Install bins, free/paid flags, freshness indicators
Estimated potential revenue
Exploratory Analysis

Univariate, bivariate & multivariate analysis
Outlier detection & handling
Visualization

Insights with Matplotlib, Seaborn & Plotly (interactive)
Key Insights
Long-Tail Engagement → ~98% of apps have <10K ratings; very few dominate.
Utility Apps Lead → Tools, Communication & Productivity top install counts.
Niche Genres Win Ratings → Role Playing, Casino & Simulation score highest.
Paid Apps Edge → Slightly higher average ratings vs. free apps.
Weak Predictors → App size & price show negligible effect on ratings.
Release Trends → Launches peaked in 2020, declined afterward.
Revenue Concentration → Casual games & productivity tools drive most revenue.
Notebook
Full analysis is available here:
Google_PlayStore_EDA.ipynb

Dataset Source: Google Play Store Apps Dataset (Kaggle)

Tech Stack
Python (Pandas, Numpy)
Matplotlib, Seaborn, Plotly
Jupyter Notebook
Conclusion & Next Steps
This EDA provides clear insights into app popularity, quality, monetization, and lifecycle trends, empowering developers, analysts, and businesses for data-driven decisions.

Next steps:

Predictive modeling for installs/ratings
Clustering & segmentation of apps
Time-series forecasting of launches & updates
Prototype recommender system
Interactive dashboard with key KPIs
This project demonstrates how structured EDA transforms raw app data into actionable strategies for growth, optimization, and product success.

If you found this project useful, don’t forget to ⭐ star this repo!
