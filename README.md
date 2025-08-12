# 🎬 Movie Recommendation System with Authentication

An interactive **Streamlit web app** that recommends movies based on content-based filtering.  
The system integrates **user authentication** with SQLite and fetches movie posters & details from **The Movie Database (TMDB) API**.

---

## 🚀 Features
- 🔑 **User Registration & Login** (SQLite database authentication)
- 🎯 **Content-Based Recommendations** using a precomputed similarity matrix
- 🖼 **Movie Posters & Details** fetched from TMDB API
- 💻 **Interactive UI** built with Streamlit
- 🔗 **Clickable Posters** linking to TMDB movie pages

---

## 🛠 Tech Stack
- **Python** (Backend)
- **Streamlit** (Frontend)
- **SQLite3** (Database)
- **Pandas & Pickle** (Data Handling)
- **TMDB API** (Movie Data)
- **LocalTunnel** (Deployment for public access)

---

## 📂 Dataset
- **`movie_list.pkl`** → Contains movie IDs and titles
- **`similarity.pkl`** → Precomputed similarity scores between movies

---

## ⚙️ How It Works
1. **Register or Log In** with a username and password.
2. **Select a Movie** from the dropdown.
3. **Get Top 5 Recommendations** with posters and direct TMDB links.

---

## ▶️ Installation & Usage

1. **Clone the repository**
   ```bash
   
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
   pip install -r requirements.txt
   ```

2. **Install dependencies**
   ```bash
   ```
   pip install -r requirements.txt
   ```

3. **Add your TMDB API key in the script:**
   ```bash
   ```
   TMDB_API_KEY = "your_api_key_here"
   ```

4. **Run the app**
   ```bash
   ```
   streamlit run app.py
   ```

# 📜 License
This project is licensed under the MIT License - feel free to use and modify it.
