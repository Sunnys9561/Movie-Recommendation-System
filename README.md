**Movie Recommendation System**

**Project Overview**

This project implements a Hybrid Movie Recommendation System using both Content-Based Filtering and Collaborative Filtering (Matrix Factorization using SVD) on the MovieLens dataset.

The system recommends personalized movies to users based on:

Genre similarity

User rating behavior

Latent interaction patterns between users and movies

**Business Problem**

With thousands of movies available, users often struggle to find relevant content.
Streaming platforms like:

Netflix

Amazon

use recommendation systems to:

Increase user engagement

Reduce churn

Improve watch time

Personalize user experience

This project simulates a real-world recommendation engine used in modern streaming platforms.

**Solution Approach**

**Content-Based Filtering**

Used TF-IDF Vectorization on movie genres

Applied Cosine Similarity

Recommends movies similar to a selected movie

**Collaborative Filtering**

Created a User-Item interaction matrix

Applied Matrix Factorization using SVD

Learned latent features representing user preferences

Predicted missing ratings

**Hybrid Recommendation System**

Combined content similarity with predicted user ratings

Improved personalization accuracy

**Technologies Used**

Python

Pandas

NumPy

Scikit-learn

SciPy (SVD)

Matplotlib

Google Colab

**Model Evaluation**

Evaluated performance using RMSE (Root Mean Squared Error)

Compared actual vs predicted ratings

Ensured model generalization through matrix reconstruction validation

 **Project Structure**
Movie-Recommendation-System/
│
├── movies.csv
├── ratings.csv
├── notebook.ipynb
├── svd_predictions.pkl
└── README.md

**Key Features**

✔ Personalized recommendations
✔ Hybrid filtering approach
✔ Manual SVD implementation (no external recommender library)
✔ Clean and modular code structure
✔ Python 3.12 compatible

**Results**

Successfully generated personalized recommendations

Captured hidden relationships between users and movies

Reduced prediction error using matrix factorization

Built scalable recommendation logic

**Future Improvements**

Add Deep Learning (Neural Collaborative Filtering)

Implement real-time API using FastAPI

Deploy interactive web app using Streamlit

Add cold-start problem handling

Use movie descriptions & embeddings for better content modeling

**Resume Impact Statement**

Designed and implemented a Hybrid Movie Recommendation System integrating Content-Based Filtering and SVD-based Collaborative Filtering. Improved personalization by modeling latent user-movie interactions and evaluated performance using RMSE.
