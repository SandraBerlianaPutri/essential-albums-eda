# Taylor Swift Discography Analysis

## About
This project explores Taylor Swift's discography using Spotify track features, album metadata, and song lyrics. The analysis focuses on audio characteristics, popularity trends, album comparisons, and lyric sentiment to identify patterns across her music catalog.

## Data
- **Dataset:** Taylor Swift Spotify track data and discography lyrics
- **Sources:** CSV datasets containing Spotify track features and song lyrics
- **Track Features:** Acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, valence, tempo, duration, and popularity
- **Album Information:** Album titles, song names, and release dates
- **Lyrics Data:** Song titles and lyrics used for text-based sentiment analysis

## Methods

1. **Data Preparation** — Load the datasets, remove duplicate songs, drop unnecessary columns, and standardize album names by consolidating deluxe editions, re-recordings, and alternate releases where applicable.
2. **Exploratory Data Analysis (EDA)** — Examine distributions of audio features, including acousticness, instrumentalness, energy, valence, tempo, popularity, and liveness.
3. **Relationship Analysis** — Use scatter plots to explore relationships between danceability and energy, loudness and liveness, valence and loudness, and popularity against track duration and speechiness.
4. **Popularity Trend Analysis** — Calculate average track popularity by release year and compare average popularity across albums.
5. **Correlation Analysis** — Create a correlation heatmap to examine relationships among numerical Spotify features.
6. **Album Comparison** — Compare album-level audio characteristics using summary statistics, bar charts, and box plots. Analyze acousticness, energy, valence, danceability, tempo, speechiness, and instrumentalness.
7. **Album Composition Analysis** — Examine the distribution of tracks across albums and categorize releases into Taylor's Version, Deluxe Edition, and other releases.
8. **Lyric Sentiment Analysis** — Preprocess song lyrics by removing line breaks and punctuation, converting text to lowercase, and applying VADER sentiment scoring.
9. **Text Visualization** — Generate a word cloud to explore frequently occurring words in the lyrics.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University, interested in data analysis and statistical visualization.
