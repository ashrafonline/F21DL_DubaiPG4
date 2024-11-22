# F21DL_DubaiPG4 - Music Analytics Using Machine Learning

## Overview
This project explores the use of machine learning techniques for analyzing, predicting, and clustering music data. It aims to uncover insights into song popularity, genre classification, and playlist generation. By leveraging advanced models, the project addresses challenges in music analytics and provides data-driven solutions to enhance the music experience.

## Objectives
* Understand key factors influencing song popularity.
* Predict song popularity using regression models.
* Classify songs into genres based on album cover images.
* Cluster songs with audio features to identify patterns and generate playlists.

## Datasets
### Spotify Tracks Dataset:
__Features:__ Genre, Popularity, Acousticness, Danceability, Duration, Energy, Instrumentalness, Key, Liveness, Loudness, Mode, Speechiness, Tempo, Time Signature, Valence.
### Album Covers Dataset:
__Features:__ Album cover images organized by genre.

## Key Features

**Regression Analysis:** Prediction of song popularity using models such as Decision Trees, Random Forest, and Gradient Boosting.

**Clustering:**  Grouping songs based on audio features using K-Means and DBSCAN for playlist generation.

**Classification:** Genre prediction from album covers using Convolutional Neural Networks (CNNs) with pre-trained models like MobileNetV2.

## Results

### Regression:

Best Model: Random Forest with optimized parameters.
* Mean Squared Error (MSE): `0.97`
* Root Mean Squared Error (RMSE): `0.99`
* R² Score: `0.997`

### Clustering:
K-Means: Best-performing clustering method with a silhouette score of `0.597`.

### Classification:

* Initial CNN accuracy: `16.45%.`
* Improved to `95.22%` for binary classification (Classical vs. Non-Classical) using MobileNetV2.

## Repository Structure and Navigation

The repository is organized into distinct folders and files to streamline access to data, models, experiments, and results. Below is a step-by-step guide to help navigate the project:

1.Data :  
`data/` : `data links.txt`: Links to the external datasets (Spotify Tracks, Album Covers).

2. Notebooks: 

`notebooks/`

* `imagesDSVisualization.ipynb`: Visualizes album cover datasets to analyze brightness, tones, and patterns.
* `AlbumCovers_Tensorflow.ipynb`: Implements classification of album covers using 
convolutional neural networks (CNNs) and TensorFlow.
* `Spotify_Audio_features_Clustering.ipynb`: Performs clustering of audio features to identify song patterns and generate playlists.(the entire notebook can only be seen if you access colab)
* `Decision_Tree_Regressor.ipynb`: Develops and evaluates a decision tree regression model to predict song popularity.
* `data_mining_linear_regression.ipynb`: Implements linear regression for predicting popularity based on key features.
* `rfr_predictionnn.ipynb`:* Implements Random Forest Regression with hyperparameter tuning.

4. Reports :  `reports/`:  final report
