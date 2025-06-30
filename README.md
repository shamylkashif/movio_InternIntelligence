# 🎬 Movio – Movie Recommendation App

Movio is a visually rich and user-friendly movie recommendation app built with **Flutter**. It fetches movie data using **TMDb API** and offers features like personalized watchlists, reviews, search filters, and user authentication.

This app is ideal for anyone looking to explore trending movies, track favorites, and engage with reviews — all through a beautifully crafted mobile experience.

---

## ✨ Features

### 👤 Authentication
- Sign Up / Login
- Forgot Password & Password Reset
- Password Verification via OTP

### 🎬 Movie Discovery
- Browse movies by rating, year, genre
- View movie posters, overviews, ratings, duration
- Explore detailed descriptions and reviews
- Add movies to personal Watchlist

### 🔍 Smart Search
- Search by title, genre, rating, release year
- View categorized results
- "See All" for extended results

### ⭐ User Profile
- Profile screen with update options
- Saved Watchlist
- Settings, Delete Account, Complaint submission

---

## 🧠 Tech Stack

- **Flutter** (cross-platform)
- **Firebase Auth** – for user login
- **Cloud Firestore** – for storing user watchlists and reviews
- **TMDb API** – for movie data
- **Provider** – for state management

---

## 📁 Project Structure Overview

lib/
├── Models/
│ └── user_model.dart
├── Provider/
│ └── movies_provider.dart
├── screens/
│ ├── Authentication/ → Sign up, Login, Reset password
│ ├── MainScreens/ → Home, Search, WatchList, Profile
│ ├── SubScreens/ → About, Complaints, Settings, Movie Descriptions, Reviews
├── Services/ → Auth logic, TMDb API handler, Firestore services
├── utils/ → App colors and themes
├── widgets/ → Reusable UI widgets (MovieCard, Buttons, Validators)
├── firebase_options.dart
└── main.dart


---

## 📌 Status
✅ **Completed (MVP)**  
---

## 📚 Learnings / Concepts Used
- REST API integration (TMDb)
- Firebase Auth & Firestore
- State management using Provider
- Clean and modular folder structure
- Reusable widget-based design
- Input validation, UX polishing

---

## 👨‍💻 Author

**Shamyl Kashif**  
- BSCS, Flutter Developer  
- [GitHub](https://github.com/shamylkashif) | [LinkedIn](https://www.linkedin.com/in/shamyl-kashif-923bb3259/)

---
