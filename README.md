# Netflix

---

# 🎬 Netflix Clone
> **"Who's watching?"** — A Full-Stack Streaming Platform Clone.

![Netflix Clone Banner](https://repository-images.githubusercontent.com/placeholder/netflix-clone-banner.png)
*(Replace this link with a screenshot or GIF of your running app!)*

---

## 🍿 Now Streaming (Overview)
This project is a pixel-perfect clone of the Netflix interface, built to demonstrate full-stack proficiency. It features a responsive React frontend with a cinematic UI, powered by a robust FastAPI backend. It fetches real-time movie data, plays trailers, and offers a seamless "Netflix-like" experience.

### 🌟 Top Features
* **Cinematic Hero Section:** Dynamic featured content with backdrop video/image support.
* **Infinite Browsing:** Horizontal scrolling rows for "Trending", "Top Rated", and "Action".
* **Instant Playback:** One-click trailer playback using the YouTube API (modal view).
* **Responsive Design:** Looks great on Mobile, Tablet, and Desktop (Mobile-first approach).
* **Real Data:** Integrated with **TMDB API** for up-to-date movie metadata and images.

---

## 🎬 Cast & Crew (Tech Stack)

### **Frontend (The Stage)**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

### **Backend (The Director)**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![TMDB API](https://img.shields.io/badge/TMDB_API-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white)

---

## 📺 How to Watch (Installation Guide)

Follow these steps to deploy your own instance of the application.

### **Episode 1: Prerequisites**
Ensure you have the following installed:
* Node.js & npm
* Python 3.11+
* MongoDB (Locally or Atlas)

### **Episode 2: The Backend Setup**
```bash
# 1. Navigate to the backend studio
cd backend

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install the script
pip install -r requirements.txt

# 4. Configure environment variables (.env)
# Create a .env file and add:
# MONGO_URL=mongodb://localhost:27017
# DB_NAME=netflix_clone
# CORS_ORIGINS=http://localhost:3000

# 5. Action! (Run the server)
uvicorn server:app --reload

```

*Backend runs on: `http://localhost:8000*`

### **Episode 3: The Frontend Setup**

```bash
# 1. Navigate to the frontend studio
cd frontend

# 2. Configure environment
# Create a .env file inside frontend/ and add:
REACT_APP_BACKEND_URL=http://localhost:8000

# 3. Install dependencies
npm install

# 4. Showtime! (Run the app)
npm start

```

*Frontend runs on: `http://localhost:3000*`

---

## 📂 Behind the Scenes (Folder Structure)

```text
netflix-clone/
├── 📂 backend/          # FastAPI Server & Logic
│   ├── server.py        # Main API endpoints
│   ├── tmdb_service.py  # TMDB integration logic
│   └── ...
├── 📂 frontend/         # React Application
│   ├── 📂 src/
│   │   ├── 📂 components/
│   │   │   ├── 📂 Netflix/   # Custom UI (Hero, Rows, Cards)
│   │   │   └── 📂 ui/        # Shadcn Reusable Components
│   │   ├── 📂 pages/         # Views (HomePage.jsx)
│   │   └── ...
└── README.md

```

---

## 🔜 Coming Soon (Roadmap)

* [ ] **User Profiles:** Create multiple profiles (Kids, Guest, etc.).
* [ ] **My List:** Save movies to your personal watchlist using MongoDB.
* [ ] **Search:** Full search functionality for movies and TV shows.
* [ ] **Authentication:** Login/Signup with JWT.

---

## 📜 Credits

**Director & Lead Developer:** [Syed Ismail N](https://www.google.com/search?q=https://github.com/syedismailn-ra)


```

```
