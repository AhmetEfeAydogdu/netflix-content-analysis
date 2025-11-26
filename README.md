# Netflix Content Analysis

## Description
This project looks at how Netflix’s content library has changed over time, focusing on the difference between Movies and TV Shows.  
The main idea is to see whether Netflix has been adding more TV Shows compared to Movies as the years go by.

The dataset used in this project comes from Kaggle:  
https://www.kaggle.com/datasets/shivamb/netflix-shows

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
The dataset includes information such as title type, release year, rating, country, duration, and genres.  
The project begins by reading the dataset, cleaning the required columns, and separating Movies and TV Shows.

The main steps include:
- Counting how many Movies and TV Shows appear each year
- Visualizing the trend over time
- Checking whether TV Shows have increased faster than Movies
- Preparing cleaned variables for further analysis and testing

No complex preprocessing is needed for this stage.

---

## Technologies Used
- Python  
- pandas  
- matplotlib  
- seaborn  
