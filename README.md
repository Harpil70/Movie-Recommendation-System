# 🎬 Movie Recommendation System

This project implements a **Content-Based Movie Recommendation System** using **Machine Learning techniques**.
It recommends movies similar to a selected movie based on **keywords, genres, overview, and tagline**.

---

## 📌 Project Overview

The system analyzes movie metadata and suggests similar movies using **TF-IDF vectorization** and the **K-Nearest Neighbors (KNN)** algorithm.

The recommendation process is based on **text similarity between movie descriptions and metadata**.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* SciPy

Machine Learning techniques used:

* TF-IDF Vectorization
* Feature Engineering
* K-Nearest Neighbors (KNN)

---

## 🧠 How the Recommendation System Works

1. The dataset is cleaned and unnecessary columns are removed.
2. Text features are combined into a single **content column**:

   * overview
   * tagline
   * keywords
   * genres
3. Text is converted into numerical vectors using **TF-IDF Vectorizer**.
4. Additional features like **popularity** and **adult flag** are included.
5. All features are combined into a single feature matrix.
6. **KNN (NearestNeighbors)** is used to find movies with similar feature vectors.

---

## 📊 Features Used

* Keywords
* Genres
* Overview
* Tagline
* Popularity
* Adult flag

These features help the system understand movie similarity.

---

## 🚀 Example Recommendation

Input:

The Dark Knight

Output:

Batman Begins
The Dark Knight Rises
Man of Steel
Batman v Superman

---

## 📂 Dataset

The dataset contains movie metadata such as:

* Title
* Genres
* Keywords
* Overview
* Popularity
* Tagline

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Run the notebook or Python script.

---

## 📌 Future Improvements

* Add a **Streamlit web interface**
* Include **movie posters**
* Implement **fuzzy search for movie titles**
* Deploy the model online

---

## 👨‍💻 Author

Harshil Patel
