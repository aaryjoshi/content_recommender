# 🎬 Movie Recommendation System

A **content-based movie recommender** that suggests similar movies based on metadata such as genres, cast, and keywords. Built with Python using **Pandas**, **Scikit-learn**, and **Cosine Similarity**, and equipped with an interactive interface for personalized movie discovery.

---

## 🚀 Features

- 🔍 Recommends similar movies based on a selected title
- 🎭 Uses content metadata: genres, cast, crew, keywords, etc.
- 📈 Implements **TF-IDF vectorization** and **cosine similarity** for relevance scoring
- 🖥️ Clean, interactive user interface for dynamic recommendations
- 🧠 Fast and lightweight — no need for ratings or external APIs

---

## 🛠 Tech Stack

- **Python**
- **Pandas**
- **Scikit-learn**
- **TF-IDF Vectorizer**
- **Cosine Similarity**

---

## 📊 How It Works

1. **Data Preprocessing**  
   - Load and clean the movie metadata dataset  
   - Combine features like genres, cast, crew, and keywords into a single textual representation  

2. **Feature Extraction**  
   - Apply **TF-IDF vectorization** to convert metadata into numerical vectors  

3. **Similarity Computation**  
   - Use **cosine similarity** to measure the closeness between movie vectors  

4. **Recommendation Engine**  
   - For a given movie title, fetch the most similar movies based on content  

---

## 📎 Example

> 🎥 Input: `"Inception"`  
> 🔁 Output: `"Interstellar"`, `"The Matrix"`, `"Shutter Island"`, `"Memento"`, `"The Prestige"`

---

## 💻 Getting Started

1. **Clone the Repository**  
```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
