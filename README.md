# spotify-dashboard

#Overall Description
This is a comprehensive Spotify Music Analytics Dashboard designed to provide insights into a library of songs, likely from a personal collection or a specific dataset. The dashboard is multi-faceted, allowing the user to explore data from various angles including artists, songs, albums, popularity, and temporal trends. It effectively uses a combination of cards, bar charts, tables, and line charts to present the data

#Detailed Analysis of Dashboard Components
The dashboard is organized into several distinct sections or report pages, as indicated by the navigation pane on the left (Songs, Home, Overview).

#1. "Songs" Page
This page appears to be a high-level overview and entry point into the data.
Key Metrics (Top KPI Cards):
28K Total Songs: The total number of songs in the dataset.
342 Distinct Artists: The number of unique artists.
89.62 Avg Popularity: The average popularity score (likely a 0-100 index provided by Spotify) for all songs, indicating a generally high-popularity collection.
3.28 Avg Duration Minutes: The average length of a song.
Artist & Song List: A detailed, scrollable table showing specific artists and one of their songs (e.g., Zeynep Bastik - "Lan", Zach Bryan - "28"). This acts as a granular data view.
Visualizations on this Page:
Popularity by Song (Bar Chart): Shows the most popular individual songs, like "Cruel Summer" by Taylor Swift and "As It Was" by Harry Styles.
Distinct Songs by Year (Bar Chart): Reveals a near-identical number of songs from 2023 (453) and 2024 (452), suggesting the dataset is very current.
British Songs by album_type (Donut Chart): Breaks down the "British Songs" subset by album type, showing more songs come from 'albums' (562) than 'singles' (269).
Avg Popularity by album_type (Bar Chart): Indicates that "compilation" and "single" album types have a higher average popularity (92) than the overall average (88).

#2. "Home" & "Overview" Pages
These pages seem to focus on specific slices or segments of the data.
"Home" Page: Contains a visual for "Explicit vs. Non-Explicit Songs," showing a count of 17K for one of these categories.
"Overview" Page: Contains a card for "Explicit..." with a count of 11K, which is likely related to the breakdown on the "Home" page.

#3. "Artist" Page (as seen in 3.png)
This page is dedicated to deep-diving into artist-specific metrics.
Popularity by Artist (Horizontal Bar Chart): Clearly ranks artists by their overall popularity in the dataset. Taylor Swift is the most popular, followed by Billie Eilish, Sabrina Carpenter, etc.
Track by Artist (Horizontal Bar Chart): Shows the average number of tracks per album for various artists. This is a measure of an artist's typical album length. Artists like John Lennon and Osiris have a high average.
Songs by Artist (Horizontal Bar Chart): Displays the total number of distinct songs by each artist in the collection. Taylor Swift leads by a significant margin (50), followed by Travis Scott (30) and Drake (27).
Artist List: A comprehensive, scrollable list of all artists in the dataset, from NSYNC to aespa.
Detailed Songs Table: A rich, tabular view of the song data with columns for:
release_date
Avg Popularity
Avg Position (potentially chart position or a internal ranking)
Avg Duration per Year / Avg Duration Minutes

#4. Temporal Trends (Line Charts)
Popularity by Month (Line Chart): Tracks the average popularity of songs over the course of a year (Jan-Dec). This can be used to identify seasonal trends in the music collection's popularity.
Distinct Songs by Month (Line Chart): Tracks the number of unique songs added or released per month, useful for understanding release cycles or data collection patterns.

#Summary of Key Insights
High-Quality, Modern Library: The high average popularity (89.62) and the focus on 2023-2024 releases indicate a collection of current, mainstream music.
Taylor Swift Dominance: Taylor Swift is a standout artist in this dataset, leading in both overall popularity and the number of distinct songs.
Balanced Recent Collection: The almost equal split of songs between 2023 and 2024 shows the dataset is very up-to-date.
Diverse Analytical Angles: The dashboard successfully allows a user to analyze data by song, artist, album type, release date, and duration, providing a 360-degree view of the music library.

#In conclusion,
this is a well-structured and insightful Power BI dashboard that effectively transforms raw Spotify data into actionable business and listener intelligence. It serves as an excellent tool for anyone looking to understand the trends and composition of this specific music collection.

### 🔗 **Interactive Dashboard**
Click below to explore the live dashboard 👇 
👉 [**View Power BI Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZDUwMDg3OTEtNGE1Yy00Yzk1LWFiMDctYTgzMDBjNDRlZmM5IiwidCI6Ijg1YmRkNjUwLWM5NmMtNGQzNy1hZDE3LTRlZWQ4MzJiM2Y0OSJ9)
