# Movie Genre Classification 🎬

## 📌 Project Overview
This project is part of the **CODSOFT Machine Learning Internship (Task 1)**.  
It uses the IMDb "Genre Classification Dataset" to predict a movie's genre based on its plot summary.

The model uses **TF-IDF** for text feature extraction and compares **Logistic Regression**, **Naive Bayes**, and **SVM** classifiers.

---

## 📂 Dataset
- **Source:** [Kaggle - Genre Classification Dataset IMDb](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)
- **Files Used:** `train_data.txt`, `test_data.txt`
- Genres merged for better balance (e.g., `fantasy` + `adventure` → `fantasy/adventure`).

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- scikit-learn
- NLTK
- Joblib

---

## 🚀 How to Run

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/MOVIE-GENRE-CLASSIFICATION.git
cd MOVIE-GENRE-CLASSIFICATION
