## Spotify Music Analysis & Recommendation System
This project focuses on building a recommendation system using a Spotify dataset. The dataset contains detailed information about songs, including audio features, artist details, release dates, and popularity metrics.
Dataset Overview

    Data Preprocessing:

    Handled missing values (e.g., filled missing tempo values using the median).

    Encoded categorical features (artists, release date) for model compatibility.

    Scaled numerical features using MinMaxScaler to ensure consistency.

    Removed outliers from key features (tempo, speechiness, liveness, duration, popularity) using IQR method.

2.Feature Selection & Dimensionality Reduction:

    Variance Thresholding to remove low-variance features.

    Principal Component Analysis (PCA) to retain only the most informative components.

    Similarity Computation & Recommendation:

    Used Euclidean distance to measure song similarity.

    Based on an input track, recommended songs with the most similar feature profiles.

Objective

Our goal is to build a robust and efficient music recommendation system that suggests songs based on their audio characteristics, helping users discover music aligned with their preferences. Unlike collaborative filtering, which relies on user interactions, our approach focuses purely on song attributes, making it ideal for recommending songs even when user history is unavailable.
