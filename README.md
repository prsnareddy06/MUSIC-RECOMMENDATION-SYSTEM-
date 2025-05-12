# MUSIC-RECOMMENDATION-SYSTEM

# Music Recommender System Project

## Project Description

This is a music recommendation system that suggests songs similar to a user's selected track. The system uses natural language processing and machine learning techniques to analyze song lyrics and recommend songs with similar lyrical content.

### Key Components:

1. **Data Processing**:
   - Uses a dataset of 57,650 songs from Spotify (spotify_millsongdata.csv)
   - Performs text cleaning and preprocessing on song lyrics
   - Applies stemming using Porter Stemmer to normalize words

2. **Recommendation Engine**:
   - Utilizes TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert lyrics into numerical representations
   - Calculates cosine similarity between songs to find the most similar tracks
   - Recommends 5 most similar songs based on lyrical content

3. **Streamlit Web Application**:
   - Provides a user-friendly interface to select songs and view recommendations
   - Displays album artwork by querying the Spotify API
   - Shows recommendations in a clean 5-column layout

4. **Spotify Integration**:
   - Uses Spotify's API to fetch album cover art for recommended songs
   - Requires Spotify developer credentials (client ID and secret)

### Technical Stack:
- Python
- Streamlit (for web interface)
- Scikit-learn (for TF-IDF and cosine similarity)
- NLTK (for text processing and stemming)
- Spotipy (Spotify API wrapper)
- Pandas (for data manipulation)

### How It Works:
1. Users select a song from the dropdown list
2. The system finds songs with the most similar lyrics using cosine similarity
3. For each recommended song, it fetches the album artwork from Spotify
4. Displays the top 5 recommendations with their album covers

This project demonstrates how natural language processing can be applied to music data to create personalized recommendations based on lyrical content.


This project has a "similarity.pkl" file which is of large storage which can be obtained but running the jupyter notebook programs.
