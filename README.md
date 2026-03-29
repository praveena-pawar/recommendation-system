# 🎬 Movie Recommendation System (Hybrid)

This project is a movie recommendation system built using the MovieLens dataset.
The goal of this project is to understand how recommendation systems work and to implement different techniques used in real-world applications.

---

## 📌 About the Project

In this project, I built a recommendation system using:

* Collaborative Filtering (based on user ratings)
* Content-Based Filtering (based on movie features)
* Hybrid Model (combination of both)

This helped me understand how platforms like Netflix and Amazon recommend content to users.

---

## 🚀 What I Implemented

### 1. Collaborative Filtering

* Created a user-movie matrix using ratings data
* Used correlation to find similar movies
* Filtered movies based on number of ratings to improve accuracy

---

### 2. Content-Based Filtering

* Used movie genres and titles as features
* Applied TF-IDF to convert text into numerical form
* Used cosine similarity to find similar movies

---

### 3. Hybrid Recommendation System

* Combined both methods
* Used weighted scoring to improve recommendations

```python
final_score = (0.6 * correlation) + (0.4 * content_score)
```

---

## 🛠 Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 📂 Dataset

I used the MovieLens dataset which contains:

* Movie details (title, genres)
* User ratings

---

## 📊 Example

```python
hybrid_recommend("Toy Story (1995)")
```

Output:

* Toy Story 2 (1999)
* Monsters, Inc. (2001)
* Bug's Life, A (1998)

---

## 🧠 What I Learned

* How recommendation systems work
* Difference between collaborative and content-based filtering
* Handling sparse data
* Importance of feature engineering
* How to combine multiple models (hybrid approach)

---

## 🔮 Future Improvements

* Add user-based recommendation
* Build a simple UI using Streamlit
* Improve model performance

---

## 👨‍💻 Author

Praveena Pawar
