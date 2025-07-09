# 🎬 Mini Movie Explorer

**Mini Movie Explorer** is a sleek, responsive React app that allows users to search for movies using the [OMDb API](https://www.omdbapi.com/), explore details, and build their own personal watchlist.

This project demonstrates modern front-end practices including debounced search, state persistence via localStorage, theming with dark mode, and UI modularity with reusable components.

---

## ✨ Features

- 🔍 **Live Movie Search with Debounce** – No unnecessary API spam; searches trigger only after the user pauses typing.
- 🎬 **Movie Detail Modal** – Click any movie card to see full details like plot, cast, ratings, etc.
- ⭐ **Watchlist Functionality** – Add movies to a watchlist that persists using localStorage.
- 🌗 **Dark/Light Mode Toggle** – Switch themes on the fly with a single click.
- 📱 **Mobile-Responsive Layout** – Clean and readable across all screen sizes.
- ⚡ **Fast Development with Vite** – Blazing fast bundling and hot reloads.

---

## 🚀 Live Demo

🌐 [View Deployed App on Vercel](https://mini-movie-explorer-three.vercel.app/)

---
## 🧠 How I Approached It

I structured the Mini Movie Explorer project with simplicity and clarity in mind, using **React** and **Vite** for a fast, modern development experience.

- I broke the UI into **reusable components** — `SearchBar`, `MovieCard`, `Watchlist`, and `MovieModal` — for modular and maintainable code.
- Used **React's `useState` and `useEffect`** hooks to manage state like search results, theme, selected movie, and watchlist.
- Implemented **debouncing** in the search bar to avoid excessive API calls and improve performance.
- The **watchlist** is saved in **localStorage**, ensuring persistence across reloads.
- **Dark mode** is applied dynamically using CSS variables and a `data-theme` attribute on the `<html>` tag.
- Clicking a movie card opens a **modal** with complete details fetched from the OMDb API.
- The layout uses CSS Flexbox and is **fully responsive** across screen sizes.

This project helped me solidify my understanding of React fundamentals, side effects, local storage, API handling, and clean UI design.

---
## 🛠 Tech Stack

- **Frontend:** React, JavaScript (ES6+), Vite
- **Styling:** Custom CSS Modules with CSS variables for theming
- **API:** OMDb (Open Movie Database)
- **Hosting:** Vercel

---

## 📦 Getting Started Locally

### 1. Clone the Repository
```bash
git clone https://github.com/anushkab2508/mini-movie-explorer.git
cd mini-movie-explorer
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Add Your OMDb API Key
Create a `.env` file in the root of the project:
```env
VITE_OMDB_API_KEY=your_omdb_api_key_here
```

### 4. Run the App Locally
```bash
npm run dev
```
The app will be available at `http://localhost:5173/`

---

## 📄 License

This project is open-source and free to use.

---

## 🙋‍♀️ Author

Built with ❤️ by **Anushka Bhandarkar**


