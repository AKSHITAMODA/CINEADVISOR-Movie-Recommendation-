# 🎬 CineAdvisor: Smart Movie Recommendation System

**CineAdvisor** is an AI/ML-powered movie recommendation system designed to enhance the way users discover movies. Built using powerful Python libraries and multiple Kaggle datasets, CineAdvisor goes beyond traditional recommendations by enabling **multi-criteria filtering** such as runtime, language, cast, director, and more.

---

## 🚀 Features

- 🎯 Personalized movie recommendations using **Cosine Similarity**
- 🔍 Advanced multi-criteria filtering:
  - Runtime
  - Language
  - Cast
  - Director
- 📦 Integrated ZIP-based metadata import from Kaggle
- 📊 Weighted rating system for fair ranking
- 📈 Visual analytics for:
  - Ratings
  - Vote count
  - Popularity
  - Revenue
- 🧹 Efficient data parsing and cleanup

---

## 📁 Datasets Used

- [TMDb 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Additional zipped metadata files (genres, keywords, cast, crew)

---

## 🛠️ Tech Stack

- Python
- Pandas & NumPy
- Matplotlib / Seaborn
- Scikit-learn (Cosine Similarity)
- Jupyter Notebook

---

## 🧮 Weighted Rating Formula

```python
WR = (v / (v + m)) * R + (m / (v + m)) * C
