# Netflix Data Analysis

## Project Overview

Netflix is one of the world's leading streaming platforms, offering thousands of movies and TV shows across different genres and countries. This project analyzes a Netflix movie dataset containing over 9,000 titles to uncover trends, perform exploratory data analysis (EDA), and generate insights that can support data-driven business decisions.

## Project Scenario

Netflix is well known for using Data Science, Artificial Intelligence (AI), and Machine Learning (ML) to understand user behavior, improve content recommendations, and optimize business strategies.

In this project, I take on the role of a Data Analyst and analyze a Netflix movie dataset using Python. The data is inspected, cleaned, transformed, and visualized to identify patterns and answer key business questions.

## Objectives

* Perform data cleaning and preprocessing.
* Explore trends in Netflix movie content.
* Analyze genres, popularity, ratings, and release years.
* Create visualizations to support findings.
* Generate business-oriented insights from the dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Business Questions

This project aims to answer the following questions:

1. What is the most frequent movie genre on Netflix?
2. How are movies distributed across different vote average categories?
3. Which movie genres have the highest average vote ratings?
4. Which movie has the highest popularity, and what is its genre?
5. Which movie has the lowest popularity, and what is its genre?
6. Which release year has the highest number of movies?

## Key Insights

*Insights will be added after completing the analysis.*

## Data Cleaning Summary

* No missing values or duplicate records were found.
* Converted `Release_Date` to datetime format.
* Extracted release years for analysis.
* Removed irrelevant columns that were not required for analysis.
* Cleaned and transformed the `Genre` column.
* Used the `explode()` function to create one genre per row.
* Categorized `Vote_Average` for better analysis.
* Examined outliers in the `Popularity` column.

## Project Structure

```text
Netflix-Data-Analysis/
│
├── data/
│   └── mymoviedb.csv
│
├── notebooks/
│   └── movie_data_analysis.ipynb
│
└── README.md
```

## Future Improvements

* MySQL integration
* Excel-based reporting
* Additional business insights
* Enhanced visualizations
* Interactive dashboard development

## Project Status

Project in progress.
