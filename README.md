# ✈️ Tourify

<div align="center">

### Smart Travel Booking & Planning Application

A modern Flutter-powered travel platform for booking flights, hotels, buses, trains, and rental cars — built with Firebase and designed with a smooth animated user experience.

<br>

![Flutter](https://img.shields.io/badge/Flutter-3.0+-02569B?style=for-the-badge&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-2.17+-0175C2?style=for-the-badge&logo=dart)
![Firebase](https://img.shields.io/badge/Firebase-Backend-FFCA28?style=for-the-badge&logo=firebase)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-black?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active%20Development-success?style=for-the-badge)

</div>

---

# 🌍 Overview

**Tourify** is a feature-rich travel booking application developed using **Flutter** and **Firebase**.  
The application simplifies travel planning by providing an all-in-one platform for:

- Flight Booking
- Hotel Reservations
- Bus Ticket Booking
- Train Ticket Booking
- Car Rentals
- User Authentication & Profile Management

The project focuses on delivering:

- Smooth UI/UX
- Modern animated interfaces
- Cross-platform performance
- Scalable Firebase backend integration
- Real-time data management

Tourify combines elegant frontend design with robust backend architecture to create a seamless digital travel experience.

---

# ✨ Features

## 🔐 Authentication System

Secure user authentication powered by Firebase Authentication.

### Included Features
- Email & Password Sign Up
- Secure Login
- Persistent User Sessions
- Logout Functionality
- Error Handling & Validation

---

## 👤 Profile Management

Users can manage and personalize their profiles.

### Profile Features
- Profile Photo Upload
- Username Management
- Email Display
- Phone Number Storage
- Firebase Cloud Storage Integration

---

# 🛫 Booking Modules

## ✈️ Flight Booking
- Browse available flights
- View travel details
- Reserve seats
- Store bookings in Firestore

---

## 🚌 Bus Booking
- Search bus routes
- Select seats
- View fare details
- Confirm reservations

---

## 🚆 Train Booking
- Choose departure & arrival stations
- Select train schedules
- Reserve train seats
- View journey details

---

## 🏨 Hotel Booking
- Browse hotels by destination
- View room options
- Select payment methods
- Confirm reservations

---

## 🚗 Car Rental
- Browse rental cars
- Select rental duration
- Configure booking options
- Review pricing & confirm booking

---

# 🎨 UI & User Experience

Tourify was designed with a strong emphasis on modern mobile UI/UX principles.

## Interface Highlights
- Animated Background Elements
- Gradient-Based Design System
- Responsive Layouts
- Smooth Navigation
- Modern Typography
- Clean Component Architecture

### Included Animations
- Flying airplane animations
- Floating cloud effects
- Smooth screen transitions
- Interactive booking cards

---

# 🏗️ Tech Stack

## Frontend
| Technology | Purpose |
|---|---|
| Flutter | Cross-platform UI framework |
| Dart | Programming language |
| Material Design | UI components |

---

## Backend & Cloud
| Technology | Purpose |
|---|---|
| Firebase Authentication | User authentication |
| Cloud Firestore | Database |
| Firebase Storage | Profile image storage |
| Firebase Core | Firebase initialization |

---

# 📱 Supported Platforms

- Android
- iOS

---

# 📂 Project Structure

```text
tourify/
│
├── android/
├── ios/
├── lib/
│   ├── screens/
│   ├── widgets/
│   ├── models/
│   ├── services/
│   ├── animations/
│   ├── utils/
│   └── main.dart
│
├── assets/
│   ├── images/
│   ├── animations/
│   └── icons/
│
├── firebase/
├── pubspec.yaml
└── README.md
```

---

# 🚀 Getting Started

## Prerequisites

Before running the project, ensure the following are installed:

- Flutter SDK (3.0.0 or higher)
- Dart SDK
- Android Studio or VS Code
- Git
- Firebase Account
- Android Emulator / iOS Simulator / Physical Device

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/0-Lucifer/Tourify.git
cd Tourify
```

---

## 2️⃣ Install Dependencies

```bash
flutter pub get
```

---

# 🔥 Firebase Setup

## Create Firebase Project

Go to:

```text
https://console.firebase.google.com
```

Enable:
- Authentication
- Firestore Database
- Firebase Storage

---

## Download Firebase Config Files

### Android
Place:

```text
google-services.json
```

inside:

```text
android/app/
```

---

### iOS
Place:

```text
GoogleService-Info.plist
```

inside:

```text
ios/Runner/
```

---

# 📦 Required Dependencies

```yaml
firebase_core: ^2.24.2
firebase_auth: ^4.16.0
cloud_firestore: ^4.14.0
firebase_storage: ^11.6.0
image_picker: ^1.0.7
google_fonts: ^6.1.0
```

---

# 🔧 Firebase Configuration

Ensure Firebase is initialized in:

```dart
main.dart
```

Also configure:

```text
android/build.gradle
android/app/build.gradle
```

according to Firebase setup instructions.

---

# ▶️ Running the Project

## Verify Flutter Installation

```bash
flutter doctor
```

Ensure all dependencies and devices are properly configured.

---

## Run the Application

```bash
flutter run
```

---

## Run in Debug Mode

```bash
flutter run --debug
```

---

# 📸 Screenshots

```text
Add your application screenshots here
```

Example:
- Login Screen
- Home Page
- Flight Booking Screen
- Hotel Booking Screen
- User Profile
- Payment UI

---

# 🔮 Future Improvements

- AI-based travel recommendations
- Online payment gateway integration
- Real-time ticket availability
- Google Maps integration
- Push notifications
- Dark mode support
- Multi-language support
- Travel itinerary generation

---

# 🧠 Architecture Highlights

## Core Design Principles

- Scalable Firebase backend
- Modular Flutter architecture
- Reusable widget system
- Clean state management
- Responsive UI design
- Optimized navigation flow

---

# 📊 Current Development Status

| Module | Status |
|---|---|
| Authentication | ✅ Completed |
| Profile Management | ✅ Completed |
| Flight Booking | ✅ Completed |
| Bus Booking | ✅ Completed |
| Train Booking | ✅ Completed |
| Hotel Booking | ✅ Completed |
| Car Rental | ✅ Completed |
| Payment Integration | 🚧 In Progress |
| Push Notifications | 🚧 Planned |

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

## Contribution Steps

```bash
Fork the repository
Create a new branch
Commit your changes
Push the branch
Open a Pull Request
```

---

# 📄 License

This project is intended for educational and academic purposes.

---

# 👨‍💻 Developer

### Lucifer Sir

Flutter Developer | Backend Integration | Firebase | Mobile Application Development

---

# ⭐ Final Note

Tourify is designed to demonstrate how modern mobile technologies like Flutter and Firebase can be combined to build a scalable, visually engaging, and feature-rich travel booking ecosystem.

The project emphasizes:
- Real-world application architecture
- Modern UI/UX design
- Cloud-based backend integration
- Scalable mobile development practices

---
