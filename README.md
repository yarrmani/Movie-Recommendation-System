# 🎬 Movie Recommendation System

A user-based **collaborative filtering** system that recommends movies to users based on their ratings and similarities with other users.  

---

## 🚀 Project Overview
This project builds a **Movie Recommendation System** that predicts movies a user might like by analyzing the preferences of similar users.  
It calculates **user similarity using cosine similarity** and recommends top-rated movies that a user hasn't seen yet.  

---

## 🗂 Dataset
- **Source:** [MovieLens 100k Dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)  
- **Files used:**
  - `u.data` → User ratings (user_id, movie_id, rating, timestamp)  
  - `u.item` → Movie details (movie_id, title)  

---

## 🔧 What This Project Does
1. Uploads and loads the dataset in **Google Colab**.  
2. Merges **ratings** and **movie titles** into a single dataframe.  
3. Creates a **user-item rating matrix**.  
4. Computes **cosine similarity** between users.  
5. Recommends movies to a user based on ratings from **similar users**.  
6. Evaluates recommendation performance using **Precision@K**.  
7. Generates a **top-5 movie list** for a subset of users.  

---

## 🛠 Libraries Used
- Python 3.x  
- Pandas & NumPy  
- Scikit-learn  

---

## 💻 How to Run
1. Open the notebook in **Google Colab**.  
2. Upload the files `u.data` and `u.item`.  
3. Run all cells to generate movie recommendations and evaluate performance.  
4. View the **Top 5 recommended movies** for each user.  

---

## 👤 Author
**Muhammad Abdurrehman**  
