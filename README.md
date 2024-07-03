# Movies recomendation system
This Streamlit app is a movie recommendation system that suggests similar movies based on a selected title. It loads movie data and similarity scores from pre-saved Pickle files. When a user selects a movie and clicks the "Recommend" button, the app fetches and displays posters and titles of the top 5 similar movies using The Movie Database (TMDB) API.

Key Points

Streamlit Framework: Uses Streamlit to create an interactive web application.

Data Loading: Loads movies data and similarity scores from Pickle files.

Movie Selection: Provides a dropdown menu for users to select a movie from a list of titles.

Recommendation Logic: Finds and displays the top 5 most similar movies based on cosine similarity scores.

API Integration: Fetches movie posters using The Movie Database (TMDB) API and displays them alongside the recommended movie titles.
