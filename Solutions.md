# Spotify Data Analysis Solutions

This document provides SQL solutions for analyzing Spotify data along with their corresponding result sets.

---

## **A. General Song Information**

### 1. What are the top 5 most streamed songs in 2023?

SELECT track_name, streams
FROM spotify
WHERE released_year = 2023
ORDER BY streams DESC
LIMIT 5;

### 2. How many unique artists are represented in the dataset?


SELECT COUNT(DISTINCT `artist(s)_name`) AS unique_artists
FROM spotify_table;

### 3. How are songs distributed across different release years?

SELECT released_year, COUNT(*) AS song_count
FROM spotify_table
GROUP BY released_year
ORDER BY released_year;

### 4. Who are the top 10 artists based on popularity, and what are the average danceability and energy levels of their tracks?


SELECT `artist(s)_name`, 
       SUM(CAST(streams AS UNSIGNED)) AS total_streams, 
       AVG(danceability_%) AS avg_danceability, 
       AVG(energy_%) AS avg_energy
FROM spotify_table
GROUP BY `artist(s)_name`
ORDER BY total_streams DESC
LIMIT 10;

### 5. Which artists released the longest and shortest songs?


-- Longest song
SELECT `artist(s)_name`, track_name, MAX(duration) AS longest_duration
FROM spotify_table;

-- Shortest song
SELECT `artist(s)_name`, track_name, MIN(duration) AS shortest_duration
FROM spotify_table;
