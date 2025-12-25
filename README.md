# 🎬 Movie Recommendation System (Content-Based Filtering)

This project implements a **Content-Based Movie Recommendation System** using **cosine similarity** and **TF-IDF vectorization**. It recommends movies to users based on the similarity of movie metadata such as genres, keywords, and descriptions.

---

## 📌 Overview

The goal of this project is to build a recommendation engine that suggests movies similar to a user's favorite based on content features. Unlike collaborative filtering, this system doesn't rely on user ratings but instead analyzes the **textual content** of movies to compute similarity.

---

## 🧠 Key Concepts

- **Content-Based Filtering**: Recommends items similar to those a user has liked in the past.
- **TF-IDF Vectorization**: Converts textual metadata into numerical vectors based on term frequency and inverse document frequency.
- **Cosine Similarity**: Measures the cosine of the angle between two vectors to determine similarity.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Numpy
- Jupyter Notebook

---


---

## 🚀 How It Works

1. **Data Preprocessing**: Load and clean movie metadata.
2. **Feature Engineering**: Combine relevant text fields (e.g., genres, overview, keywords).
3. **Vectorization**: Apply TF-IDF to convert text into feature vectors.
4. **Similarity Computation**: Use cosine similarity to find movies closest to the input.
5. **Recommendation Output**: Return top-N most similar movies.

---

## 📈 Evaluation

The system was evaluated using:
- **Top-N Accuracy**
- **Precision & Recall**
- **Qualitative inspection of recommendations**

---

## 📌 Example

If a user likes *Inception*, the system might recommend:
- Interstellar
- The Matrix
- Shutter Island

---

## 📚 Future Improvements

- Incorporate user ratings (hybrid approach)
- Use word embeddings (e.g., Word2Vec, BERT)
- Build a web interface with Flask or Streamlit

---

## 🤝 Contributions

Feel free to fork this repo, open issues, or submit pull requests to improve the system!

---

