# 🎵 Spotify Wrapped, Rewritten: An Exploratory Dive into Music Trends (2000–2019)

## 📖 Overview

This project explores two decades of Spotify’s top hits (2000–2019) using data analytics and visualization. By analyzing audio features like danceability, energy, valence, tempo, loudness, and acousticness, alongside artist and genre trends, the project uncovers patterns that shaped global playlists.

Think of it as Spotify Wrapped — but powered by data.

## 📁 Dataset

The dataset used in this project can be found [here](https://github.com/raksha9917/spotify-wrapped-eda/blob/main/Tophits2000-2019.csv).

Rows: ~20 years of top tracks data

Columns include:
1. Songs
2. Artist
3. Release Year (Year)
4. Genre
5. Duration (ms → converted to min:sec for certain DataFrames only)
6. Audio features: danceability, energy, valence, tempo, speechiness, acousticness, instrumentalness, liveness, loudness, key
7. Explicit
8. Popularity

## 🛠 Tech Stack
1. Python - Programming & Analysis
2. Jupyter Notebook – interactive coding & visualisation
3. Pandas – data wrangling & cleaning
4. NumPy – numerical operations
5. Matplotlib – plotting & customisation
6. Seaborn – statistical visualisation (heatmaps, KDEs, scatterplots)
7. Plotly (optional) – interactive charts

## 📊 Methods
1. Data Cleaning & Preparation
   - Checked for missing values and duplicates
   - Converted duration from milliseconds → minutes:seconds

2. Exploratory Data Analysis (EDA)
   - Songs released per year
   - Most popular artists across two decades
   - Trends in song duration over time
   - Distribution of major vs minor keys
   - Genre evolution (2000–2019)
   - Audio feature distributions (energy, valence, danceability, etc.)
   - Correlation between features
   - Outliers: longest & shortest hit songs

3. Visualisations
   - Histograms, bar plots, scatter plots, KDE plots, pie charts, correlation heatmaps, stacked area charts

## 🚀 Results & Insights
   - Songs are getting shorter — streaming favors quick hooks.
   - Minor keys on the rise — moodier tracks are climbing the charts.
   - Pop dominates, but hip-hop & EDM surged in the 2010s.
   - Danceability & energy remain hit-makers — high replay value is key.
   - Energy ↔ Loudness correlation strong, but tempo ↔ valence less predictable.

## 📎 Links
- 📖 Blog Post: [here](https://rakshanama.blog/2025/09/05/spotify-wrapped-rewritten-an-exploratory-dive-into-music-trends/)
- 📂 Dataset: [here](https://github.com/raksha9917/spotify-wrapped-eda/blob/main/Tophits2000-2019.csv) 
- 💻 Notebook: [here](https://github.com/raksha9917/spotify-wrapped-eda/blob/main/SpotifyEDA.ipynb)

