# News App — Flutter App

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white)](https://dart.dev)
[![State%20Mgmt-Riverpod](https://img.shields.io/badge/State%20Mgmt-Riverpod-5C8DBC)](https://riverpod.dev)
[![Router-GoRouter](https://img.shields.io/badge/Router-go__router-blueviolet)](https://pub.dev/packages/go_router)
[![Backend-Supabase](https://img.shields.io/badge/Backend-Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com)
[![Platforms](https://img.shields.io/badge/Platforms-Android%20%7C%20iOS-lightgrey)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A modern Flutter-based News Application with a clean **dark UI**, **trending news slider,** category-based search, and detailed news reading experience.
This project focuses on clean UI design, **API integration,** and scalable Flutter architecture.

---

## ✨ Features

- 🚀 Splash Screen with App Branding

- 🔥 Trending / Hottest News Carousel

- 🧠 Personalized “News For You” Section

- 🔍 Search News by Keyword (e.g. Tech, Business, Politics)

- 📰 News Details Page with Image, Title, Author & Date

- 🌙 Dark Theme UI

- 📱 Bottom Navigation Bar

- ⚡ Smooth Navigation using GetX

- 📦 Clean & Scalable Project Structure

---

## 📸 Screenshots

> Place the `screenshots/` folder in your repo root so these links work on GitHub.

<p align="center">
  <img src="Assets/files/screenshots/main.jpg" style="width:100%; max-width:100%;" alt="News App Main Screen"/>
</p>

<img src="Assets/files/screenshots/1.jpeg" width="260"  alt=""/> <img src="Assets/files/screenshots/2.jpeg" width="260" /> <img src="Assets/files/screenshots/3.jpeg" width="260" />

<img src="Assets/files/screenshots/4.jpeg" width="260" /> <img src="Assets/files/screenshots/5.jpeg" width="260" /> <img src="Assets/files/screenshots/6.jpeg" width="260" />

---

## 🎥 Demo

<p><img src="Assets/files/screenshots/demo.gif" width="420" alt="News App demo GIF"/></p>

## 🧱 Tech Stack

📌 Frontend

- Flutter (Material 3)
- Dart
- Getx / MVVM pattern

📌 Third-Party APIs

- News API (news data)
- HTTP Package – API requests
- REST API – News data source

---

## 🚀 Getting Started

### 🔑 API Configuration

- Flutter **3.x** and Dart **3.x**
- Create an account on a News API provider
- Get your API key
- Add the key inside your config file:
- Like this const String apiKey = "YOUR_API_KEY_HERE";

### Prerequisites

- Flutter SDK installed

- Android Studio / VS Code

- Emulator or Physical Device

### Setup

```bash
# 1) Clone
git clone https://github.com/amhimel/news-app.git
cd <your-repo>

# 2) Install packages
flutter pub get
```

### Run

```bash
flutter run
```

---

## 📁 Suggested Folder Structure

```
lib/
│
├── components/        # Reusable UI components
├── config/            # API configuration & constants
├── controller/        # GetX controllers (state management)
├── models/            # Data models (NewsModel, etc.)
├── pages/             # App screens (Home, Search, Details)
├── widgets/           # Custom widgets
│
├── main.dart          # App entry point



```

---

### 📌 Current Limitations

- No offline caching yet

- No authentication system

- No push notifications

## 🚧 Future Improvements

- 🔔 Push Notifications
- 💾 Offline News Caching
- 🧑‍💻 User Profile & Preferences
- 🌍 Category-based News Tabs
- 📊 Better Error Handling & Empty States

---

## 🤝 Contributing

PRs are welcome!  
If you spot UI/UX tweaks, accessibility fixes, or performance improvements, please open an issue first to discuss the change.

---

## 📝 License

MIT © 2025-12-21 — News App Contributors
