# 📚 Book Recommendation System

A Machine Learning based Book Recommendation System that suggests books similar to a given book using collaborative filtering and cosine similarity.

---

## 🚀 Project Overview

This project recommends books based on user preferences and book similarity.  

The system allows users to:

- View **Top Rated Books**
- Search a book
- Get **similar book recommendations**
- Explore book details like **author, rating, and votes**

---

## 🧠 Machine Learning Approach
The recommendation engine uses:

- **Collaborative Filtering**
- **Cosine Similarity**
- **User-Book Rating Matrix**

### Workflow
User Input (Book Name)
↓
Book-User Matrix
↓
Cosine Similarity Calculation
↓
Find Similar Books
↓
Display Recommendations

---

## 🗂 Project Structure
book-Recommendation-System
│
├── app.py
├── requirements.txt
├── README.md
│
├── Data
│ ├── Books.csv
│ ├── Ratings.csv
│ └── Users.csv
│
├── model
│ ├── books.pkl
│ ├── popular.pkl
│ ├── pt.pkl
│ └── similarity_scores.pkl
│
├── templates
│ ├── index.html
│ ├── recommend.html
│ └── contact.html
│
└── notebooks
  └── recommendation_model.ipynb

---

## 🛠 Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-Learn
- HTML
- CSS
- Bootstrap

---

## 📊 Dataset

- Books information
- User ratings
- User data

Files used:

- Books.csv
- Ratings.csv
- Users.csv

---


## ✨ Features

- Top Rated Books display
- Book Recommendation Engine
- Error Handling for invalid book names
- Modern responsive UI
- Contact Page

---

