# 🎬 CineSearch — MERN Movie Search & Favourites App

A MERN (MongoDB, Express, React, Node.js) web application that allows users to search movies using the **OMDB API**, view search results, and mark movies as **favourites**.
Favourites are stored on the backend using simple server-side storage (in-memory or file-based).

---

## 🚀 Features

### 🔍 Movie Search

* Debounced search input (prevents excessive API calls)
* Fetches movies from **OMDB API**
* Displays results with:

  * Movie poster
  * Title
  * Release year

### ❤️ Favourites System

* Add or remove movies from favourites using a heart icon
* Favourites are stored on the backend (Node/Express)
* Favourites persist on page reload

### 💻 Tech Stack

**Frontend**

* React
* Axios / Fetch API
* Tailwind / CSS (your choice)

**Backend**

* Node.js
* Express
* MongoDB or File Storage (as per requirement)

---



## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/cinesearch.git
cd cinesearch
```

### 2️⃣ Install frontend dependencies

```bash
cd client
npm install
```

### 3️⃣ Install backend dependencies

```bash
cd ../server
npm install
```

---

## 🔑 Environment Variables

### Client (.env)

```
REACT_APP_OMDB_API_KEY=your_api_key
```

### Server (.env)

```
PORT=5000
MONGO_URI=your_mongo_connection_string   # If using MongoDB
```

---

## ▶️ Running the App

### Start Backend

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm run dev   # or npm start
```

---

## 🛠 API Endpoints

### **GET /favorites**

Returns list of favourite movies.

### **POST /favorites**

Adds a movie to favourites.

### **DELETE /favorites/:id**

Removes a movie from favourites.

---





## 🙌 Contact

For queries or contributions, feel free to open an issue or reach out!

---

