# Taylor Swift Song Recommender & Lyric Searcher 🎶

This project is a data science exploration of Taylor Swift's music, offering a song recommendation system and a lyric search tool using data from Spotify and Genius. The project is divided into four main sections and includes a bonus Taylor Swift Emoji Quiz at the end for some extra fun!

## Sections
1. [Data Visualization 👀](#data-visualization)
2. [Song Recommender 🎧](#song-recommender)
3. [Lyric Searcher 🔍](#lyric-searcher)
4. [Keyword Search Tool 🔑](#keyword-search-tool)
5. [Taylor Swift Emoji Quiz 💯](#taylor-swift-emoji-quiz)

---

## Data Visualization 👀

In this section, we use visualizations to explore Taylor Swift's music, focusing on:
- The number of songs released each year.
- Relationships between audio features like "Loudness" and "Energy."
- Trends in the popularity of Taylor Swift's songs over time.

We also dive into:
- **Most Popular Song**: Identify the most popular Taylor Swift song on Spotify.
- **Minor Key Songs**: Explore how many of her songs are written in a minor key, album by album.

---

## Song Recommender 🎧

The song recommender system allows you to input a song from the `billions_club` dataset (a collection of popular songs from Spotify) and get recommendations of Taylor Swift songs that have a similar sound, based on audio features like:
- Danceability
- Energy
- Valence
- Acousticness
- Instrumentalness

The recommendation system calculates the similarity between the input song and Taylor Swift's discography using **Euclidean distance**.

### Example Usage:

You can interactively select a song from the `billions_club` and receive the five most similar Taylor Swift songs. Customize the recommendation by selecting which features to compare.

---

## Lyric Searcher 🔍

The lyric searcher allows you to search for phrases in Taylor Swift's song lyrics. This tool lets you:
- Search for exact or partial phrases, case-insensitive.
- See surrounding lyrics for more context.
- Discover which songs contain your phrase.

### Example Search:
- Searching for the phrase **"casually cruel"** will return lines from **"All Too Well (10 Minute Version)"** and **"Mr. Perfectly Fine"**.

---

## Keyword Search Tool 🔑

This tool allows you to perform deep keyword searches across Taylor Swift's lyrical body of work. You can:
- Identify and display all songs containing a specific keyword.
- See not only the matching lines but also the lines before and after, providing context for the phrase.

---

## Taylor Swift Emoji Quiz 💯

Test your knowledge of Taylor Swift's songs with an emoji-based quiz! Try to identify Taylor Swift songs based on emoji descriptions, and see how many you can get right.

---

## Data Sources 📊
1. **Lyrics Data**: Obtained from [Genius](https://genius.com/) – the largest collection of song lyrics.
2. **Audio Features Data**: Retrieved from [Spotify](https://www.spotify.com/), using its proprietary feature analysis.

---
