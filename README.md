# 🎬 Movie Recommender System
This project builds a content-based movie recommendation system that suggests movies similar to a given title based on key features like genres, keywords, cast, crew, and overview.

The core idea is to process textual metadata from a movie dataset and compute cosine similarity scores, allowing users to find the top 5 most similar movies for any selected film.

## 🔍 What This Project Does

- 📦 Merges and cleans TMDB’s **movie** and **credits** datasets  
- 🧠 Extracts and processes key features: `genres`, `keywords`, `cast`, `crew`, and `overview`  
- 🏷️ Creates a combined **“tags”** feature for every movie  
- ✨ Transforms text into numerical vectors using `CountVectorizer` (removes stop words, top 5000 words)  
- 🔗 Computes pairwise **cosine similarity** between movies  
- 🧾 Saves preprocessed data and similarity matrix using `pickle`  
- 🌐 Offers a real-time movie search & recommendation interface using **Replit**
