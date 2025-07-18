# 🎬 Movie Recommendation System

This is a simple content-based movie recommendation system built using Python and the TMDB movies metadata dataset. It recommends movies based on plot similarity using TF-IDF vectorization and cosine similarity.

---
## 📁 Dataset
Due to GitHub’s file size limit, the dataset is not included here.

You can download it from:  
🔗 [The Movie Dataset (Kaggle)](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
## 📌 Features

- Recommend movies based on a movie you like
- Uses Natural Language Processing (NLP) to compare overviews
- Simple and beginner-friendly code using Pandas, Scikit-learn, and Numpy

---

## 🧠 How It Works

- Loads movie data from a CSV file (`movies_metadata.csv`)
- Cleans and processes the movie overviews
- Uses **TF-IDF Vectorizer** to convert text into numerical form
- Calculates **cosine similarity** between movies
- Recommends the top 5 most similar movies

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Libraries: pandas, numpy, scikit-learn

### Install dependencies

```bash
pip install pandas numpy scikit-learn
