# Analyzing Netflix Content Trends
#### A Data-Driven Exploration of Genres, Ratings, and Global Contributions


## Overview
This project performs a comprehensive data analysis of Netflix titles from 2021. The analysis explores various aspects of Netflix content, including genre distribution, country contributions, release trends, content duration, and rating categories. The goal is to derive insights into how content has evolved over time and its current distribution across different categories.

## Key Features:
1. Growth of Movies and TV Shows: Analyze content additions over time.
2. Genre Distribution: Explore popular genres and their prevalence across Movies and TV Shows.
3. Country Contribution: Investigate which countries contribute the most content.
4. Content Duration: Compare the length of Movies and TV Shows.
5. Rating Categories: Analyze the distribution of content based on rating categories (e.g., TV-MA, PG-13).
6. Advanced Visualizations: Scatter plots, histograms, boxplots, and heatmaps are used to explore various relationships.

## Table of Contents
1. Installation
2. Usage
3. Data Cleaning and Preparation
4. Analysis
5. Visualizations
6. Questions Addressed
7. Technologies Used
8. License

## Installation

### 1. Clone the repository:  
  git clone https://github.com/your-username/netflix-content-analysis.git

### 2.  Install the required Python libraries:  
  pip install pandas, numpy, matplotlib.pyplot, seaborn

## Usage
1. Load the Netflix dataset (netflix_titles_2021.csv) using the script.
2. Run the Jupyter Notebook or Python script to perform the analysis.
3. Visualize the insights generated from the dataset.


## Example Commands:

  import pandas as pd  
  import numpy as np  
  import matplotlib.pyplot as plt  
  import seaborn as sns  
    
  df = pd.read_csv('netflix_titles_2021.csv')  
  df.head()  

## Data Cleaning and Preparation
The dataset was cleaned by handling missing values in critical columns like date_added, rating, and duration. The dataset contains 12 columns, including title, genre, director, country, release year, and duration.

1. Missing Values: Dropped rows with missing values in critical columns.
2. Data Types: Ensured proper data types for each column, including numerical and categorical data.

## Analysis
### Key analysis performed includes:

1. Growth Analysis: Number of movies and TV shows added over the years.
2. Genre Exploration: The distribution of genres and their popularity over time.
3. Country of Origin: Top contributing countries in terms of Netflix content.
4. Content Duration: Analysis of duration patterns across movies and TV shows.
5. Rating Categories: Distribution of content across different age rating categories.

## Visualizations
### The project uses various visualizations to illustrate key findings, including:

1. Histograms for content release year and duration.
2. Bar Charts for genre distribution, country contributions, and ratings.
3. Boxplots for comparing content duration across genres.
4. Scatter Plots to analyze the relationship between release year and duration.

## Questions Addressed
### This project answers several important questions about Netflix's content library:

1. How has Netflix content grown over the years?
2. Which genres are the most prevalent, and how do they differ between movies and TV shows?
3. What are the top countries contributing to Netflix's content?
4. Are there any trends in content duration or length across different categories?
5. How does the distribution of content vary by rating categories?

## Technologies Used
1. Python: Core programming language.
2. Pandas: Data manipulation and analysis.
3. NumPy: Numerical operations.
4. Matplotlib: Data visualization.
5. Seaborn: Advanced data visualization.
6. Jupyter Notebook: For running and documenting analysis.

