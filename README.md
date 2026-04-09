# Movie recommendation system

## Project overview
This project is a comprehensive movie recommendation system that suggests films based on content similarity. It covers the entire data science lifecycle: from automated data collection via the **TMDb API** to building an interactive web application using **Streamlit**.

## Team Collaboration
This project was developed as a collaborative team effort. Working in a team allowed us to implement an end-to-end pipeline, from data engineering to web deployment, while maintaining high code quality and documentation standards.

**Contributors:**
* **Makhabbat** — [Role, e.g., Data Collection & API Integration]
* **Nurila** — [Role, e.g., Machine Learning & Vectorization]
* **Zhaniya** — [Role, e.g., UI Development & Streamlit Interface]

### 1. Data collection (TMDb API)
* Automated retrieval of over 2,000 movies using the TMDb API.
* Handled pagination and extracted metadata including titles, genres, ratings, and poster URLs.
* Data stored in a structured CSV format for further processing.

### 2. Data cleaning & preprocessing
* **Missing Value Imputation:** Filled gaps in release years, vote counts, and IMDB ratings.
* **Feature Engineering:** Combined genres, descriptions, and ratings into a unified "Content" column to facilitate similarity calculations.
* **Normalization:** Prepared numerical data for consistent analysis.

### 3. Recommendation engine
* **Vectorization:** Used **TF-IDF (Term Frequency-Inverse Document Frequency)** to transform text data into numerical vectors.
* **Similarity Metric:** Implemented **Cosine Similarity** to calculate the distance between movies and identify the top N most similar films.

### 4. Interactive web interface (Streamlit)
* Developed a user-friendly UI where users can select a movie from a dropdown menu.
* Real-time display of recommendations including movie posters, IMDB ratings, and similarity scores.

## Tech stack
* **Language:** Python
* **Data Handling:** Pandas, NumPy
* **NLP & ML:** Scikit-learn (TfIdfVectorizer, cosine_similarity)
* **Web Framework:** Streamlit
* **APIs:** The Movie Database (TMDb)
