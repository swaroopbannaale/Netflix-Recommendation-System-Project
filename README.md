# Netflix-Recommendation-System-Project
Description Builds a collaborative filtering recommendation system using Netflix's 24M+ customer ratings across 4,500+ movies using SVD (Singular Value Decomposition). Cleans/segments data (470k+ users), implements scikit-surprise, and personalizes movie recommendations with 3-fold cross-validation (RMSE ≈0.97)
Overview
Netflix dataset analysis using matrix factorization (SVD) to predict user ratings and recommend unwatched movies. Processes customer-movie pairs with data cleaning (removes customers/movies below 36 and 908 rating thresholds respectively) for model robustness.
​
Dataset
Size: 24M+ ratings, 4,500+ movies, 470k+ unique customers
​
Source: Netflix movie dataset (combined data + metadata CSV)
​
Format: Customer ID, Rating (1-5), Movie ID, Release Year, Title
​
Key Features
Data Cleaning: Removes sparse users/movies; filters low-rating counts for data quality
​
Model: SVD algorithm via scikit-surprise; 3-fold cross-validation
​
Metric: RMSE ≈0.97 (predicts ratings within ±1 point)

Expected Output
Personalized top-N movie recommendations per user
Recommendations with estimated scores for each unwatched movie
Example: Movie "Dinosaur Planet" → predicted 3.67 rating

