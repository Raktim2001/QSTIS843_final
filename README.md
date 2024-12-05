Readme: Cinema Insights Project
Project Name: Cinema Insights
Team Members: Aru Pandey, Raktim Verma, Shiven Sharma

Introduction
The film industry is highly competitive, with only a fraction of movies achieving critical and commercial success. This project leverages IMDb data to identify key factors driving movie popularity and profitability. The findings aim to help filmmakers, producers, and marketers optimize creative and financial decisions.

Dataset
Source: IMDb Public Dataset from BigQuery
Tables Used:
title_basics: Details about genres, runtime, release year.
title_ratings: Audience ratings and scores.
title_principals: Cast and crew information.
title_crew: Details on directors and writers.
Custom datasets: totalscore_df.csv and revenue_df.csv.
Steps
Data Cleaning:

Removed irrelevant columns (job, characters, etc.).
Handled missing values systematically.
Leveraged PySpark for efficient processing.
Key Insights:

Genres: Drama and Comedy dominate; Western and Film-Noir are niche.
Runtime Trends: Increased until the 1950s, slight decline post-2000s.
Actor and Director Influence: Strong correlation with IMDb ratings.
Budget and Revenue: Larger budgets correlate with better ratings and revenue.
Machine Learning Models:

Random Forest: Focused on genres, director scores, and sentiment analysis.
XGBoost: High efficiency with structured data, highlighting audience preferences.
Performance Metrics: RMSE and cross-validation for model evaluation.
Results
Runtime, genres, and sentiment analysis align with movie success.
Director and actor popularity significantly impact ratings and profitability.
Budget allocation varies by genre, with Animation, Adventure, and Sci-Fi requiring the highest budgets.
Challenges
Missing data in runtime and crew details.
High dimensionality with categorical features.
Limited review data for sentiment analysis.
Future Scope
Enhance NLP techniques for advanced sentiment analysis.
Address data quality issues for robust predictions.
Explore causal relationships for deeper insights.
How to Run
Clone the repository.
Ensure dependencies (PySpark, Pandas, Scikit-learn) are installed.
Execute the Jupyter Notebook (QST1-Cinema-Insights.ipynb) for analysis and visualization.
Review presentation (qst final report.pptx) for a summary of findings.
Conclusion
This project showcases the potential of data-driven approaches to guide the film industry, highlighting actionable insights through machine learning and exploratory data analysis.

