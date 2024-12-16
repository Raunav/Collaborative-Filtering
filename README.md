# Collaborative-Filtering
This project involves building a movie recommendation system using user-based collaborative filtering with the k-Nearest Neighbors (KNN) algorithm.

# Movie Recommendation System Using User-Based Collaborative Filtering

## Overview
This project involves building a movie recommendation system using user-based collaborative filtering with the k-Nearest Neighbors (KNN) algorithm. The model was trained on the Movielens 100k dataset, utilizing 80% of the data for training and the remaining 20% for evaluation. 

The project also explores a bonus implementation of item-based collaborative filtering, comparing its performance with user-based collaborative filtering.

## Objectives
- Develop a movie recommendation system using user-based collaborative filtering.
- Train the model on 80% of the dataset and evaluate it on the remaining 20%.
- Analyze and interpret the performance using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

## Dataset
- **Movielens 100k Dataset**: [Movielens 100k](https://grouplens.org/datasets/movielens/100k/)

## Key Steps
### 1. Data Loading and Exploration
- Load the dataset to understand its structure and handle missing values (if any).

### 2. Data Preprocessing
- Transform the dataset into a format suitable for user-based collaborative filtering.

### 3. Data Splitting
- Hide 20% of ratings from 20% of users for testing.
- Use the remaining data to predict the hidden ratings.

### 4. User-Based Collaborative Filtering
- Implemented using k-Nearest Neighbors (KNN).
- Compute user similarity using:
  - Cosine similarity
  - Pearson Correlation
- Predict ratings based on similar users' ratings.

### 5. Evaluation
- Use metrics like MSE and RMSE to compare predicted ratings against actual ratings.

### 6. Results and Analysis
- Discuss model strengths and limitations.
- Analyze the performance of user-based collaborative filtering.

### Bonus: Item-Based Collaborative Filtering
- Implemented item-based collaborative filtering.
- Compared the approach with user-based collaborative filtering to highlight differences in performance.

## Results
- Detailed analysis of user-based and item-based collaborative filtering.
- Insights into similarities, accuracy, and limitations of both approaches.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---
© 2024 Raunav Sharma | All Rights Reserved
