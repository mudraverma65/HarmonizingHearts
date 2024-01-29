# Harmonizing Hearts: A Music-Based Compatibility Analysis

## Introduction
"Harmonizing Hearts" delves into the intricate interplay between music preferences and online dating dynamics. Leveraging Spotify data, this project explores the hypothesis that shared musical tastes significantly contribute to relationship success in the online dating realm. The study focuses on user matching, song clustering, and song popularity classification. This was developed as a project for course CSCI6515: ML for Big Data.

## Objectives
### Part 1: Similar User Matching
- Refined an advanced recommendation algorithm through hyperparameter tuning.
- Utilized song features such as danceability and energy.
- Implemented collaborative filtering and content-based filtering for identifying users with similar music preferences.

### Part 2a: Song Clustering and Exploration
- Clustered songs based on audio features using algorithms like K-means.
- Provided users with an interactive interface to explore songs within clusters.

### Part 2b: Song Popularity
- Trained multiple models to classify song popularity.
- Popularity score of more than 70 indicates popularity in songs.

## Datasets Used
### Dataset 1: spotify_data.csv
- Created for applying recommender models using collaborative and content-based filtering.
- Contains 250 anonymous Spotify users, each with around 100 songs.
- Features extracted from Spotify API.

### Dataset 2: track_features.csv
- Consists of 17,996 unique songs with various attributes.
- Target variable 'Class' categorizes each song into genres.
- Test dataset with 7,713 rows for model evaluation.

### Dataset 3: spotifydata.csv
- Analyzes the behavior between valence and Spotify API measures.
- Contains 232,725 tracks across 26 genres.
- Features include key, mode, time signature, and others.

## Sources
- [Spotify Dataset (kaggle.com)](https://www.kaggle.com/datasets/andrewmvd/spotify-playlists?select=spotify_dataset.csv)
- [Spotify 12M Songs Dataset (kaggle.com)](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs)
- [Ultimate Spotify Tracks Dataset (kaggle.com)](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db)

## Conclusion
Through a multifaceted approach, "Harmonizing Hearts" aims to unravel the nuanced role of music in forging connections within the realm of online dating. The project explores patterns in song features, provides interactive song exploration, and classifies song popularity, shedding light on whether a shared melody can truly harmonize hearts.
