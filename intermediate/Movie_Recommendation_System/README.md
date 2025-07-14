# 🎬 Movie Recommendation System (Content-Based)

This project builds a simple movie recommender using **content-based filtering**. Given a movie, the system recommends similar movies based on shared genres.

---

## 📁 Dataset

- The dataset contains movie titles and their genres.
- We process the `Genre` column to create a combined `tags` field for each movie.

---

## 🧠 Concepts Used

- Text preprocessing
- `CountVectorizer` to convert genre tags into numerical vectors
- Cosine similarity to measure how similar two movies are
- A function to return the top 5 most similar movies

---

## 💡 How It Works

1. Genres are cleaned and combined into a new column called `tags`.
2. `CountVectorizer` transforms these tags into a matrix of token counts.
3. Cosine similarity is computed across all movie vectors.
4. When a movie name is input, the system returns the 5 most similar movies.

---

## 🧪 Example

```python
recommend("(500) Days of Summer")

