# 🎬 Movie DB App

A modern **Android Movie Database application** built using **Kotlin**
The app allows users to explore popular movies, top-rated movies, and search movies with multiple filters.

This project demonstrates **modern Android development practices**, **clean architecture**, and a **smooth UI experience**.

---

## ✨ Features

- 🔥 **Popular Movies** – Browse trending and popular movies
- ⭐ **Top Rated Movies** – Discover highly rated movies
- 🔍 **Search Movies** – Search movies by name
- 🏷️ **Filters**
  - Rating based filters (9.8+, 9.0+, 8.0+)
  - Year based filter (2024+)
  - Production house filter (DC)
- 🎨 **Modern UI** built with Jetpack Compose
- 📱 **Bottom Navigation** for smooth screen switching

---

## 🖼️ App Screenshots

| Splash Screen | Popular Movies | Top Rated Movies | Search Movies |
|--------------|----------------|------------------|---------------|
| <img src="https://github.com/user-attachments/assets/fec24038-f683-4de8-89f8-e256db4b7d94" width="250"/> | <img src="https://github.com/user-attachments/assets/915d8fe6-2dde-49b7-bb82-5372484e5412" width="250"/> | <img src="https://github.com/user-attachments/assets/fa306933-921d-4fe2-9c80-294cf855f96a" width="250"/> | <img src="https://github.com/user-attachments/assets/b0e8b6b4-51f6-4086-8307-8976bb582a68" width="250"/> |


---


## 🎥 Movie Details Screen

The Movie Details screen provides complete information about a selected movie, including its poster, title, rating, release date, runtime, genres, and overview. Users can watch the trailer or share the movie, offering a rich and engaging movie discovery experience.

<p align="center">

  <img src="https://github.com/user-attachments/assets/9c7dbd4f-a1c4-49d7-af6d-d6986e3f80b1" width="400"/>
</p>

---

## 🛠️ Tech Stack

- **Language**: Kotlin  
- **UI**: Kotlin
- **Architecture**: MVVM  
- **Networking**: Retrofit  
- **State Management**: ViewModel + StateFlow  
- **Image Loading**: Coil  
- **Navigation**: Navigation Component  

---

## 🧱 Architecture

The app follows **MVVM architecture**:

- **UI Layer (Layout Screens)** – Displays state from ViewModel
- **ViewModel** – Manages UI state and business logic
- **Repository** – Handles data operations
- **Remote Data Source** – Fetches data from Movie API

This ensures:
- Separation of concerns  
- Scalability  
- Testability  

---
