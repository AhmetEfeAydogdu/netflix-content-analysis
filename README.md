# Netflix Content Analysis

## Description
This project looks at how Netflix’s content library has changed over time, focusing on the difference between Movies and TV Shows.  
The main idea is to see whether Netflix has been adding more TV Shows compared to Movies as the years go by.

The datasets used in this project comes from Kaggle and StatCrunch:  
- https://www.kaggle.com/datasets/shivamb/netflix-shows 
- https://www.statcrunch.com/app/index.html?dataid=2188684
- https://www.kaggle.com/datasets/thedevastator/netflix-imdb-scores
- Machine Learning: https://www.kaggle.com/datasets/ggtejas/tmdb-imdb-merged-movies-dataset

---

## Research Question & Hypothesis
**Research Question:**  
How has the balance between Movies and TV Shows changed over the years on Netflix?

**H₀ (Null Hypothesis):**  
There is no meaningful difference in the number of Movies and TV Shows released over the years.

**H₁ (Alternative Hypothesis):**  
As years increase, Netflix releases more Movies compared to TV  Shows.

This hypothesis will be examined using simple exploratory data analysis, yearly content counts, and trend-based comparisons.

---

## Features
- Yearly distribution of Movies and TV Shows  
- Movie vs TV Show counts and comparisons  
- Plots showing how content types change over time  
- Duration and season information cleaned into numeric form  
- Basic hypothesis testing based on yearly trends  

---

## How It Works
The "netflix_titles" dataset includes information such as title type, release year, rating, country, duration, and genres.  
The project begins by reading the dataset, cleaning the required columns, and separating Movies and TV Shows.

The main steps include:
- Counting how many Movies and TV Shows appear each year
- Visualizing the trend over time
- Checking whether TV Shows have increased faster than Movies
- Preparing cleaned variables for further analysis and testing

---

## Examining the Reasons Behind Observed Result
According to observed results, this project aims to detect reasons behind the difference/no difference between movie and TV show
counts using "netflix_imdb_Scores" and "movies_budget_revenue" datasets. Project focuses on three main factors:
- User engagement and attention
- Sustained attention and risk in TV show production
- Economic considerations, ROI factor

---

## Machine Learning
In the machine learning part, project uses a new dataset called "ml_movies_dataset". Using this dataset, project aims to predict movies'
IMDB ratings using different features such as budget, TMDB ratings, budget, revenue, both IMDB and TMDB vote counts , runtime, and
release year. Later on project compares different ML models according to their MAE, RMSE, AND R^2 values, and finds the best model.
Finally, feature importance analysis is done on the best model.

---

## Technologies Used
- Python  
- pandas  
- matplotlib  
- seaborn
- scikit-learn
