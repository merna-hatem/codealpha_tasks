# Music Recommendation System
## Overview:
This project aims to develop a music recommendation system using various machine learning techniques, including the RandomForestClassifier. The goal is to provide personalized music recommendations to users based on their listening history and preferences. 
## Dataset Description:
* msno: Unique identifier for each user.
* song_id: Unique identifier for each song.
* source_system_tab: The section of the app where the song was played.
* source_screen_name: The name of the screen where the song was played.
* source_type: The type of source from which the song was played.
* target: The target variable indicating whether the user liked the song (1) or not (0).
* song_length: Length of the song.
* genre_ids: Genre(s) of the song.
* artist_name: Name of the artist.
* composer: Name of the composer.
* lyricist: Name of the lyricist.
* language: Language of the song.
* city: City of the user.
* bd: Age of the user.
* gender: Gender of the user.
* registered_via: Registration method of the user.
* registration_init_time: Registration date of the user.
* expiration_date: Subscription expiration date of the user.
## Project Steps:
### 1. Data Collection
* Load the dataset containing user listening history, song metadata, and user ratings.
### 2. Data Preprocessing
* Data Cleaning: Handle missing values and remove inconsistencies.
* Feature Encoding: Convert categorical features into numerical values.
* Exploratory Data Analysis (EDA): Analyze the dataset to understand distributions, correlations, and other key statistics.
### 3. Building the Recommendation System
* Collaborative Filtering:
 * User-Based Collaborative Filtering: Recommend songs based on the listening history and preferences of similar users.
 * Item-Based Collaborative Filtering: Recommend songs similar to those the user has already liked.
* Machine Learning Model: Use RandomForestClassifier to predict the likelihood of a user liking a song based on the available features.
### 4. Model Training and Evaluation
* Training the RandomForestClassifier: Train the RandomForestClassifier on the preprocessed data.
## Conclusion:
The music recommendation system aims to enhance user experience by providing personalized music recommendations. By leveraging collaborative filtering, content-based filtering, and machine learning techniques like RandomForestClassifier, the system can suggest songs that users are likely to enjoy, thereby increasing user engagement and satisfaction. The RandomForestClassifier model achieved an accuracy of 72%, indicating a good level of performance for the recommendation task.
