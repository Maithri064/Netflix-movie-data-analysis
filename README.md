# Netflix-movie-data-analysis

## Project Overview

This project focuses on analyzing a Netflix movies dataset to uncover insights about movie trends, genres, popularity, and ratings. The goal is to perform data cleaning, transformation, and visualization to better understand patterns in the dataset.
## Technologies Used
Python 🐍
Pandas (Data Cleaning & Analysis)
NumPy
Matplotlib & Seaborn (Data Visualization)
Jupyter Notebook
## Data Cleaning Steps
Loaded dataset using Pandas
Checked dataset structure using .info() and .describe()
Removed duplicate records
Converted Release_Date to datetime and extracted year
Dropped unnecessary columns:
Overview
Original_Language
Poster_Url
Handled missing values using dropna()
Split multiple genres and normalized data using explode()
## Feature Engineering
Categorized Vote_Average into:
Not Popular
Below Average
Average
Popular
## Exploratory Data Analysis (EDA)
1. Most Frequent Genre
Identified the most common genres using count plots.
2. Vote Distribution
Analyzed how movie ratings are distributed.
3. Most & Least Popular Movies
Found:
Movie with highest popularity
Movie with lowest popularity
4. Movies Released Per Year
Visualized number of movies released over time using histogram.
## 📈 Key Insights
Certain genres dominate Netflix content.
Most movies fall into mid-range popularity categories.
Movie releases vary significantly across years.
Popularity and ratings don’t always correlate directly.
