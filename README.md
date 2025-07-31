# codtechtask4
# 🎬 Movie Recommendation System

This project is a **Movie Recommendation System** developed using Python. It recommends movies to users based on content similarity and possibly collaborative techniques (if included). The focus is on providing relevant movie suggestions using features like genres, keywords, overview, cast, and crew.

---

## 📌 Objective

To build a system that helps users discover movies similar to their preferences using content-based techniques.

---

## 🛠️ Tools & Libraries Used

- Python
- Jupyter Notebook
- `pandas`, `numpy`
- `scikit-learn` – for vectorization and similarity computation
- `nltk` – for text preprocessing (if applied)
- `ast`, `json` – for data parsing
- `cosine_similarity` – for computing similarity scores

---


---

## 🔍 How It Works

1. **Data Loading**
   - Load movie and credits datasets (e.g., from TMDB 5000 dataset).
   
2. **Data Preprocessing**
   - Merge datasets
   - Clean and extract important features like genres, keywords, overview, cast, and director

3. **Feature Engineering**
   - Create a new feature by combining selected attributes into a single string (`tags`)

4. **Text Vectorization**
   - Use `CountVectorizer` or `TfidfVectorizer` to convert `tags` to numerical vectors

5. **Similarity Calculation**
   - Compute pairwise cosine similarity between all movies

6. **Recommendation**
   - For a given movie title, return the top 5–10 most similar movies

---

## ▶️ How to Run

1. Clone this repository or download the notebook.
2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn nltk

