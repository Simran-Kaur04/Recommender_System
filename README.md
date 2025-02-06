🎬 Movie Recommender System

📌 Project Overview

This project is a Movie Recommender System built using the TMDB 5000 Movies dataset from Kaggle. The system suggests movies to users based on content similarity using Natural Language Processing (NLP) techniques.

📂 Dataset

Source: TMDB 5000 Movies dataset

Contains: Movie metadata such as genres, cast, crew, overview, and keywords

Download: [TMDB Dataset] (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

🛠️ Steps Involved

1️⃣ Data Preprocessing

Loaded the dataset and removed missing values.

Extracted relevant columns (title, overview, genres, cast, and keywords).

Merged relevant text data into a single tag for each movie.

2️⃣ Feature Engineering

Applied Bag of Words (BoW) model to convert text data into numerical vectors.

Used CountVectorizer to create a numerical representation of movie tags.

Computed cosine similarity to measure the closeness of movie vectors.

3️⃣ Recommender System Implementation

Similarity Scores: Calculated pairwise similarity between movies.

Recommendation Function: Returns the top 5 most similar movies based on a given movie title.

📊 Example Usage

recommend_movies('Batman begins')

Output:

1. The Dark Knight
2. Batman
3. Batman
4. The Dark Knight Rises
5. 10th & Wolf

🛠️ Technologies Used

Python

Pandas, NumPy (Data Processing)

NLTK, Scikit-learn (Text Processing & Machine Learning)

Jupyter Notebook
