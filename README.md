# 🔎 Academic Search Engine

A Flask-based Academic Search Engine that retrieves and ranks relevant Wikipedia documents using **TF-IDF (Term Frequency–Inverse Document Frequency)** and **Cosine Similarity**.

---

## 📌 Project Description

This project implements an Information Retrieval (IR) system that allows users to enter a search query and receive ranked academic content from Wikipedia.

The system:

- Fetches related Wikipedia documents
- Converts text into TF-IDF vectors
- Computes cosine similarity between query and documents
- Ranks documents based on similarity score
- Displays top 5 most relevant results

This project demonstrates practical implementation of core Information Retrieval concepts.

---

## 🚀 Features

- 🔍 Real-time search functionality
- 📚 Wikipedia document retrieval
- 📊 TF-IDF computation
- 📈 Cosine similarity ranking
- 🏆 Top-5 relevant document display
- 🖥️ Clean Flask web interface
- 📄 Summary preview of each result

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Flask**
- **Scikit-learn**
- **NumPy**
- **Wikipedia API**
- **HTML (Jinja2 Templates)**

---

## 📂 Project Structure
Academic_Search_Engine/
│
├── app.py
├── requirements.txt
├── README.md
└── templates/
└── index.html


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository


git clone https://github.com/brindha-sivaperuman/Academic_Search_Engine.git


### 2️⃣ Navigate to Project Folder


cd Academic_Search_Engine


### 3️⃣ Install Required Packages


pip install -r requirements.txt


### 4️⃣ Run the Application


python app.py


### 5️⃣ Open in Browser


http://127.0.0.1:5000/


---

## 🧠 Working Principle

1. User enters a search query.
2. Wikipedia API retrieves related topics.
3. Document summaries are collected.
4. Text data is transformed into TF-IDF vectors.
5. Cosine similarity is calculated between query and documents.
6. Documents are ranked in descending order of similarity.
7. Top 5 relevant results are displayed to the user.

---

## 📊 Algorithms Used

### 🔹 TF-IDF (Term Frequency – Inverse Document Frequency)

Measures importance of words in documents relative to the entire corpus.

### 🔹 Cosine Similarity

Computes similarity between query vector and document vectors.

\[
Cosine Similarity = \frac{A \cdot B}{||A|| \times ||B||}
\]

---

## 🎯 Output Display

For each ranked document, the system shows:

- Rank position
- TF value
- IDF value
- TF-IDF score
- Cosine similarity score
- Document URL
- Summary preview

---

## 🎓 Academic Relevance

This project demonstrates:

- Information Retrieval concepts
- Vector Space Model
- Text preprocessing
- Ranking algorithms
- Web integration with Flask

---

## 👩‍💻 Author

**Brindha Sivaperuman**  
GitHub: https://github.com/brindha-sivaperuman

---

## 📜 License

This project is developed for academic and educational purposes.