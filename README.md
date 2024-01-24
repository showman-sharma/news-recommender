# News Recommendation System 

**Author:** V S S Anirudh Sharma

## Overview

This Jupyter notebook documents the implementation and analysis of a recommendation system for iPrint, an emerging media house in India. The objective is to personalize user experiences by recommending relevant news articles based on search history and preferences.

The project is divided into two main parts:

1. **Top 10 Relevant Article Recommendations:**
   - Impute rating values based on interaction types.
   - Extract English articles from the platform content.
   - Explore and analyze features in the data set.
   - Build recommendation techniques, including user-based collaborative filtering, item-based collaborative filtering, content-based filtering, ALS, and hybrid models.

2. **Top 10 Similar News Articles Recommendations:**
   - Track user clicks to understand new interests.
   - Implement different models for generating recommendations.
   - Experiment with hybrid models.
   - Evaluate the recommendations using appropriate metrics.
---
## Contents

1. **Data Pre-processing:**
   - Imputation of ratings.
   - Creation of 'consumer_interactions' dataset.
   - Extraction of English articles.

2. **Exploratory Data Analysis (EDA):**
   - Distribution analysis of various features.
   - Exploration of interaction types, locations, and languages.

3. **Recommendation Techniques:**
   - User-based Collaborative Filtering.
   - Item-based Collaborative Filtering.
   - Content-based Filtering.
   - ALS (Alternating Least Squares).
   - Hybrid Recommendation System.

4. **Model Evaluation:**
   - Use of RMSE, MAE, and precision@k metrics.
   - Evaluation of content-based models using TF-IDF scores.
   - Assessment of overall performance with global precision@k.
---   

## Conclusion and Next Steps

This notebook provides a comprehensive overview of the recommendation system development for iPrint. The implemented models and evaluations aim to enhance user engagement by offering personalized content recommendations.

Further iterations and improvements can be explored based on the insights gained during the analysis.

---

### Note 

Make sure to run the code cells sequentially for accurate results.

Ensure the following directory structure before running.
```
│   news_recommender.ipynb  
│
└───data
│   │   consumer_transanctions.csv
│   │   platform_content.csv
```
