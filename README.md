# Spotify_Data_Analysis_2023_SQL_Project

<img src="https://storage.googleapis.com/pr-newsroom-wp/1/2023/05/2024-spotify-brand-assets-media-kit.jpg" jsaction="" class="sFlh5c FyHeAf iPVvYb" style="max-width: 1920px; height: 201px; margin: 0px; width: 353px;" alt="Logo and Brand Assets — Spotify" jsname="kn3ccd" aria-hidden="false">

## Table Of Contents
  - [Introduction](#introduction)
  - [Dataset Description](#dataset-description)
  - [Potential Use Cases](#potential-use-cases)
  - [Getting Started](#getting-started)
  - [Exploratory Analysis](#exploratory-analysis)
  - [Relevant Insights](#relevant-insights)
  - [Relevant Links](#relevant-links)

---

## Introduction 

Welcome to the `"Spotify Music Analysis - 2023"` project! This project explores a comprehensive dataset of Spotify's most popular tracks of 2023. The dataset includes details about each track's attributes, streaming metrics, and cross-platform visibility, offering a rich resource for analyzing music trends.

The purpose of this analysis is to uncover insights into popular music characteristics, artist influence, and platform-specific trends while exploring various SQL-based queries to derive actionable insights.

---

## Dataset Description 

The [dataset](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023) provides detailed information about Spotify’s top tracks of 2023. It includes audio features, streaming counts, and metadata about tracks' performance across Spotify, Apple Music, Deezer, and Shazam.

### Key Features 

1. `track_name`: Name of the song.
2. `artist_name`: Name of the artist(s) of the song.
3. `artist_count`: Number of artists contributing to the song.
4. `released_year`: Year of song release.
5. `released_month`: Month of song release.
6. `in_spotify_playlists`: Number of Spotify playlists the song is featured in.
7. `in_spotify_charts`: Presence on Spotify charts.
8. `streams`: Total number of streams on Spotify.
9. `bpm`: Beats per minute (tempo).
10. `danceability_%`: Danceability score of the track.
11. `valence_%`: Musical positivity percentage.
12. `energy_%`: Energy level of the song.

For a full list of features, refer to the dataset link provided below.

---

## Potential Use Cases

- **Music Analysis**: Understand trends in popular music attributes.
- **Platform Comparison**: Compare a track's performance across Spotify, Apple Music, and other platforms.
- **Temporal Trends**: Analyze how music features have changed over time.
- **Artist Influence**: Study how artist involvement impacts track success.
- **Cross-Platform Presence**: Identify tracks that dominate multiple platforms.

---

## Getting Started 

1. **Dataset**: Download the dataset from the provided link ([Spotify Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)).
2. **Tools Used**: This project uses SQL for data exploration and analysis.
3. **Queries and Insights**: All SQL queries and derived insights are documented in this repository.

---

## Exploratory Analysis

### General Song Information:
- Top 5 most streamed songs in 2023.
- Number of unique artists in the dataset.
- Distribution of songs by release year.
- Top 10 artists based on popularity.

### Spotify Metrics:
- Songs with the highest number of Spotify playlists.
- Correlation between streams and chart presence.
- Average BPM and danceability of the top 15 songs.

### Platform Comparisons:
- Tracks present on both Spotify and Apple Music charts.
- Trends in Deezer charts based on release month.

### Audio Features:
- Differences in danceability percentages based on song mode.
- Trends in energy and acousticness across release years.

---

## Relevant Insights

- The most streamed song in 2023 had over 1 billion streams.
- Songs in major keys tend to have higher danceability scores.
- Artists with higher popularity scores also show higher average energy levels in their tracks.

Explore more insights in the [`insights.md`](insights.md) file.

---

## Relevant Links

- [Spotify Dataset - Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)
- [SQL Formatter](http://www.dpriver.com/pp/sqlformat.htm)

---

## Contributing

Contributions are welcome! If you'd like to add new questions, enhance existing solutions, or provide additional insights, feel free to fork this repository and submit a pull request.

---

## Support

For any questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/sainathreddy-panga ).

If you found this project helpful, consider giving it a ⭐ to show your support!
