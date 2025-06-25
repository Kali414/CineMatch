# 🎬 CineMatch - Content-Based Movie Recommender System

CineMatch is an interactive Streamlit-based web app that suggests movies similar to the one you choose. It uses content-based filtering powered by machine learning and The Movie Database (TMDb) API to fetch movie posters.

## 🔧 Features

- Content-based movie recommendations
- Interactive dropdown using Streamlit
- Real-time poster fetching from TMDb
- Lightweight and beginner-friendly

## 🚀 How It Works

1. You select a movie from the dropdown list.
2. The app computes similarity using a precomputed model (`similarity.pkl`).
3. Top 5 most similar movies are shown with poster images using the TMDb API.

## 🧠 Tech Stack

- 🐍 Python
- 🧵 Streamlit
- 📦 Pickle
- 🌐 TMDb API

## 📂 Files

- `app.py` — Main Streamlit app
- `movie_list.pkl` — Preprocessed movie metadata
- `similarity.pkl` — Precomputed similarity matrix
- `.env` — Securely stores API key
- `requirements.txt` — Python dependencies

## ⚙️ Setup

1. Clone the repo
    ```bash
    git clone https://github.com/Kali414/CineMatch.git
    cd CineMatch
    ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
    ```
3. Add your TMDb API key to a .env file:
   ```bash
   TMDB_API_KEY=your_api_key_here
    ```
4. Run the app:
    ```bash
   streamlit run app.py
    ```



