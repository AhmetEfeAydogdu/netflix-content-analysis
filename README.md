# film-music-alignment

### Project Overview

This project examines the alignment between films and their original soundtracks by analyzing measurable attributes. It investigates how film-level features (genre, runtime, audience rating, popularity) correspond with musical characteristics of the associated soundtrack (tempo, energy, mode, key). The objective is to identify statistical relationships and build a predictive model to explore whether musical features can serve as indicators of film style and reception.

### Objectives

Combine publicly available film metadata and soundtrack datasets to form an integrated dataset of film-soundtrack pairs.

Conduct exploratory data analysis (EDA) and statistical tests to explore relationships between film attributes and corresponding musical features.

Develop and evaluate a regression model to predict film audience rating using musical features and film metadata.

Provide insights on whether soundtrack properties reflect film style and performance, and discuss potential implications for film scoring.

### Motivation

Analytical Relevance: Quantitative study of film-music interplay fills a gap in empirical research on soundtrack design.

Practical Application: Understanding how musical properties correlate with film success could inform creative decisions in film production and scoring.

Educational Value: The project integrates data cleaning, visualization, statistical inference, and machine learning—aligning with DSA210 learning outcomes.

### Dataset

IMDb Movie Dataset (Kaggle): Contains film attributes such as title, year, genre, runtime, vote_average, popularity.

Movie Soundtracks Dataset (Kaggle): Contains soundtrack attributes such as title, bpm, energy, mode, key, track_duration.

### Analysis Plan

Data Preprocessing & Feature Engineering: Clean merged dataset, remove duplicates/missing values, standardize numeric variables.

Exploratory Data Analysis: Visualize distributions and relationships—histograms of bpm, energy, vote_average; scatter plots bpm vs vote_average, energy vs popularity; boxplots of musical features by film genre.

_**Statistical Testing:**_

ANOVA test to evaluate whether soundtrack tempo (bpm) differs significantly across film genres.

Two-sample t-test comparing soundtrack energy between popular (upper-30% popularity) and less popular films.

**_Machine Learning:_**

Linear Regression model: Predict vote_average from predictors [bpm, energy, runtime, popularity].

Evaluate using R² and RMSE.

### Expected Results

Correlation results indicating relationships between musical features and film ratings/popularity.

Significant genre differences in soundtrack attributes based on ANOVA/t-test results.

Regression model demonstrating to what extent musical and film metadata explain audience ratings (expectation: moderate R²).

Visualizations to support findings (scatter plots, boxplots, correlation heatmap).

### Conclusion

By examining the quantitative alignment between film attributes and soundtrack features, this study aims to provide empirical insight into the role of music in film perception and reception. While musical features alone may not fully explain audience ratings, they offer meaningful explanatory power and open pathways for further exploration in film-music analytics.

**_Tools & Technologies_**

Python Libraries: pandas, numpy, matplotlib, scikit-learn, scipy

Development Environment: Jupyter Notebook or Visual Studio Code

**_References_**

IMDb Movie Dataset — Kaggle.

Movie Soundtracks Dataset — Kaggle.
