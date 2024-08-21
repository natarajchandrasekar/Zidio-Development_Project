# Zidio-Development_Project

🎥 Movie Recommendation System
Welcome to the Movie Recommendation System project! This repository contains the code and documentation for a comprehensive movie recommendation engine developed as part of my application for the Zidio Development Internship

Project Overview
In this project, I implemented four different recommendation engines using various techniques and algorithms to deliver personalized movie suggestions:

Simple Recommender:

Built using TMDB Vote Count and Vote Averages to create Top Movie Charts.
The IMDB Weighted Rating System was employed to calculate ratings for sorting.
Content-Based Recommender:

Developed two content-based models:
One based on movie overviews and taglines.
Another based on metadata such as cast, crew, genre, and keywords.
A filtering mechanism was added to prioritize movies with higher votes and ratings.
Collaborative Filtering:

Utilized the Surprise Library to build a collaborative filter using single value decomposition (SVD).
Achieved a Root Mean Square Error (RMSE) of less than 1, ensuring accurate user-specific predictions.
Hybrid Engine:

Combined content-based and collaborative filtering approaches.
Provided personalized movie recommendations by calculating internal ratings for each user.
Technologies Used
Python: Programming language
Surprise Library: For collaborative filtering and SVD
Pandas & NumPy: Data manipulation and processing
Scikit-learn: Machine learning algorithms and data processing
Matplotlib & Seaborn: Data visualization
