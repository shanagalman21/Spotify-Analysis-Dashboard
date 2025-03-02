# Spotify-Analysis-Dashboard

![dashboard](https://github.com/user-attachments/assets/161c1f50-a895-4be1-9a75-cc340dc3a35b)
[Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTE3ZTQwMGEtZDVlZC00OThjLWEzMGUtNjBhNmYwMzQzZDdmIiwidCI6ImJkMDNhNzM1LTJhYTMtNGNjYS05NzIyLTJhZTQ5MjlhYjNlYyIsImMiOjEwfQ%3D%3D)

## Project Description:
An interactive Power BI dashboard that analyzes a dataset of 954 records containing [Spotify's most streamed songs of 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023). The dashboard provides insights into streaming patterns, track release trends, top-performing songs and artists, and musical characteristics of the tracks.

## Key Features:
- **Stream Trends:** Displays a line graph showing streaming trends which can be filtered by year, month, and day for a more granular view.
- **Track Trends:** Visualizes the release trends of songs over time. Includes filters for year, month, and day to explore specific periods.
- **Top Tracks and Artists:** Ranks songs and artists based on the number of streams.
- **Musical Features:** Displays key characteristics of a selected track, including: Acousticness, Danceability, Energy, Liveness, Instrumentalness, Speechiness, Valence, Key, BPM, Mode

## Process:
1. Raw data was downloaded from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023).
2. Used the Spotify Web API in Python to fetch song and album cover URLs.
3. Generated an updated dataset containing a new image URL column.
4. Cleaned the updated dataset using Power Query to produce more accurate results.
5. Built the Power BI dashboard to visualize and analyze the data.


