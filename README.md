# Spotify Music Trends Analyzer

A Data Science and Machine Learning web app that analyses 114,000 Spotify songs to uncover music trends, audio feature patterns, and predicts song popularity.

## Live Demo
https://spotify-music-trends.streamlit.app

## Problem Statement
Most music artists and producers rely on intuition when creating songs. This app uses real Spotify data to answer — what actually makes a song popular?

## Solution
An interactive dashboard that analyses audio features across genres and predicts how popular a song will be based on its characteristics.

## Features
- Top 10 most popular songs visualisation
- Genre vs audio features comparison (energy, danceability, acousticness)
- Mood analysis by genre using valence scores
- Genre filter dropdown to explore specific genres
- ML-powered song popularity predictor using Random Forest
- Song search with radar chart showing audio feature breakdown

## Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn
- Streamlit
- Scikit-learn
- NumPy

## Dataset
- Source: Kaggle — Spotify Tracks Dataset by maharshipandya
- Size: 114,000 songs across 114 genres
- Features: danceability, energy, valence, tempo, acousticness, speechiness and more

## ML Model
- Algorithm: Random Forest Regressor
- Features used: danceability, energy, valence, tempo, acousticness, speechiness
- Accuracy: R² score of 0.86

## Key Insights
- Afrobeat is the happiest genre (highest valence)
- Ambient is the saddest genre (lowest valence)
- High danceability and energy correlate with higher popularity

## How to Run Locally
```bash
git clone https://github.com/Abhisyanth-M/spotify-analytics
cd spotify-analytics
pip install -r app/requirements.txt
streamlit run app/dashboard.py
```

## Limitations
- Popularity prediction is approximate as human music taste is subjective
- Dataset is a snapshot and does not reflect real-time Spotify data

## GitHub
https://github.com/Abhisyanth-M/spotify-analytics
