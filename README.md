# 🎬  Movie_Recommendation_System

This is a simple Movie Recommendation System built using Python and Machine Learning techniques.
It suggests movies based on title similarity using TF-IDF Vectorization and Cosine Similarity.

🚀 Features

Asks the user for a movie title.

Finds the closest match using string similarity (difflib).

Recommends similar movies based only on the title.

🛠️ Tech Stack

Python 3

Pandas – for dataset handling

Scikit-learn – for TF-IDF Vectorizer and Cosine Similarity

Difflib – for matching user input to closest movie title

📂 Dataset

The dataset used contains:

Movie titles

(You can replace it with larger datasets like TMDB or IMDB for more powerful recommendations.)

📌 How It Works

Convert movie titles into vectors using TF-IDF Vectorizer.

Compute cosine similarity between movies.

Take user input (movie name).

Find the closest matching title using difflib.get_close_matches().

Recommend top similar movies.

▶️ Usage
# Clone repo
git clone https://github.com/your-username/movie-recommendation-system.git

# Install dependencies
pip install -r requirements.txt

# Run the project
python movie_recommendation.py

📊 Example Output
Enter your favorite movie: Avatar  

Movies suggested for you:
1. Guardians of the Galaxy  
2. Star Wars: The Force Awakens  
3. The Avengers  
4. Interstellar  
5. Jurassic World  

🌟 Future Improvements

Add cast, director, genre, tagline for better recommendations.

Use content-based filtering with multiple features.

Deploy as a web app with Streamlit/Flask.
