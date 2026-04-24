# 🚀 DevForce
**Tinder for Developers | Built for GDG Hackathon**

DevForce is a location-based matching and collaboration platform designed exclusively for developers. Whether you're looking for a co-founder, a mentor, or just someone to pair-program with locally, DevForce connects you with the right talent using proximity mapping and intelligent matchmaking.

---

## ✨ Features

* **🔥 Swipe Matchmaking:** Intuitive Tinder-style swipe interface to discover nearby developers based on their skills and tech stack.
* **📍 Proximity Map:** A high-performance, real-time OpenStreetMap integration that shows where developers are located around you (completely free and zero-cost map engine).
* **💬 Real-Time Chat:** WhatsApp-style messaging system with instant updates, unread message badges, time-ago formatting, and read receipts.
* **🔔 Push Notifications:** Integrated Firebase Cloud Messaging (FCM) to alert you when you get a new match or a message, even when the app is in the background.
* **🎨 Premium UI/UX:** Stunning glassmorphism design, fluid animations, and dynamic animated mesh backgrounds for a state-of-the-art feel.
* **🔒 Secure Authentication:** Powered by Google Cloud Identity and Firebase.

## 🛠 Tech Stack

* **Framework:** Flutter (Dart)
* **Backend & Database:** Firebase Firestore (NoSQL real-time database)
* **Authentication:** Firebase Auth
* **Notifications:** Firebase Cloud Messaging (FCM)
* **Maps:** `flutter_map` (OpenStreetMap) + `geolocator`
* **Architecture:** Stream-based reactive UI

## 📱 Screenshots & UI Highlights

The app heavily utilizes custom `GlassCard` widgets, `BackdropFilter` for blur effects, and dynamic gradients to create a highly polished, premium experience expected from modern hackathon winners.

## 🚀 Getting Started

### Prerequisites
* Flutter SDK (latest version)
* Android Studio / VS Code
* An Android/iOS device or emulator

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/devforce.git
   cd devforce
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Firebase Configuration:**
   * DevForce requires a `google-services.json` file to connect to the backend.
   * Place your `google-services.json` inside the `android/app/` directory.
   * *(Note: For GDG Hackathon judges, if the repository is private, the configuration file might be included for ease of testing. Otherwise, you will need to link your own Firebase project).*

4. **Run the app:**
   ```bash
   flutter run
   ```

## 🤝 GDG Hackathon Submission

This project was built during the GDG Hackathon. We focused heavily on creating a completely free, highly performant stack (avoiding paid Google Maps APIs in favor of OpenStreetMap) while delivering a premium user experience and real-time backend functionality.

---
*Built with ❤️ by Nikhil for GDG*
