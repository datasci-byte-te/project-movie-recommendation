# 🎬 Cast & Director Based Movie Recommendation System

This project is a simple content-based movie recommendation system that suggests similar movies based on cast and director using machine learning and NLP techniques.

## 📌 Objective

Build a recommender system that takes a movie title as input and returns the top 5 most similar movies using the cast and director metadata.

## 🧠 Approach

- Extract cast and director information from `credits.csv` (TMDb data)
- Preprocess and clean the text data
- Combine the top 3 cast members and the director into a single string ("soup")
- Use TF-IDF vectorization to convert the text into numerical form
- Compute cosine similarity between all movies
- Return the top 5 similar movies for any given title

## 🧰 Tech Stack

- Python 🐍
- Pandas
- Scikit-learn
- TfidfVectorizer
- Cosine Similarity
- Pickle (for saving model files)

