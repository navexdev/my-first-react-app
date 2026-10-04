# 🎬 Movie App

A responsive movie discovery web application built with **React** and **Vite**. The app allows users to search for movies, browse popular titles, view movie information, and keeps track of trending searches using **Appwrite**.

This project was built as part of my journey learning modern React development and working with external APIs and backend services.

## ✨ Features

* 🔎 Search for movies using the TMDB API
* 🎞️ Browse popular movies
* 📈 Track trending movie searches
* ⚡ Debounced search to reduce unnecessary API requests
* 🌀 Loading states and spinner
* 🎬 Reusable movie card components
* 📱 Responsive design
* 🌐 External API integration
* ☁️ Appwrite database integration

## 🛠️ Technologies

* **React**
* **Vite**
* **JavaScript**
* **TMDB API**
* **Appwrite**
* **CSS**
* **ESLint**


## 🚀 Getting Started



### 1. Install dependencies

```bash
npm install
```

### 2. Configure environment variables

Create a `.env.local` file in the root directory and add your TMDB API key:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
```

Add the required Appwrite configuration according to your project setup.

> ⚠️ Never commit your `.env` or `.env.local` files. API keys and other private credentials should remain secret.

### 3. Start the development server

```bash
npm run dev
```

The application will then be available through the local development URL shown in your terminal.



## 📚 What I Learned

Through this project, I practiced:

* Building reusable React components
* Working with React Hooks
* Fetching and displaying data from an external REST API
* Managing component state
* Creating custom hooks
* Implementing debounced search
* Working with environment variables in Vite
* Connecting a frontend application to Appwrite
* Organizing a React project
* Handling loading and empty states

## 🔮 Future Improvements

* Add movie detail pages
* Add genre filtering
* Add pagination or infinite scrolling
* Improve accessibility
* Improve error handling
* Add user favorites/watchlist functionality

## 👨‍💻 Author

**Navid Rahimi**

This project was built as part of my journey learning React and modern frontend development.