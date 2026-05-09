# Tourify

Tourify is a Flutter-based mobile application designed to streamline travel planning by allowing users to book flights and manage their profiles. It integrates Firebase for authentication, Firestore for data storage, and Firebase Storage for profile photo uploads. The app features a modern, user-friendly interface with animations and a gradient-themed design, providing a seamless experience for users to sign up, log in, view their profiles, and manage flight bookings.

## Features

- **User Authentication**: Secure sign-up and login using Firebase Authentication with email and password.
- **Profile Management**: View and manage user details (username, email, phone, and profile photo) stored in Firestore.
- **Flight Booking**: Browse and book flights with details stored in Firestore (supports future expansion for bus, train, and hotel bookings).
- **Bus Booking**: Search and reserve bus tickets with route, seat and fare details.
- **Train Booking**: Choose departure and arrival stations, book train tickets with trip, seat and fare details.
- **Animated UI**: Engaging background animations (e.g., flying plane, floating clouds) for an immersive experience.
- **Responsive Design**: Built with Flutter for cross-platform compatibility (iOS and Android).
- **Firebase Integration**: Uses Firestore for user and booking data, Firebase Storage for profile photos, and Firebase Authentication for user management.
- **Hotel Booking**: Select a destination, view hotels, choose rooms and a payment method, see the total, and confirm the reservation.
- **Car Rental**: Browse cars, set rental dates/options, review the price, choose payment, and confirm the booking.


## Prerequisites

To run Tourify on your computer, ensure you have the following installed:

- **Flutter**: Version 3.0.0 or higher (stable channel recommended).
- **Dart**: Included with Flutter.
- **Firebase Account**: A Google Firebase project set up for Authentication, Firestore, and Storage.
- **Android Studio** or **VS Code**: For Flutter development and running the app.
- **Git**: To clone the repository.
- **An emulator or physical device**: For testing the app (Android/iOS emulator or a connected device).

## Installation

Follow these steps to set up and run Tourify on your local machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/0-Lucifer/Tourify.git
   cd Tourify

   # Project Setup Instructions

1. **Install Flutter Dependencies**  
   ```bash
   flutter pub get
   ```

2. **Set Up Firebase**  
   - Create a Firebase project at [console.firebase.google.com](https://console.firebase.google.com).  
   - Enable Authentication (Email/Password provider), Firestore Database, and Storage.  
   - Download the Firebase configuration files:  
     - For Android: `google-services.json` (place in `android/app/`).  
     - For iOS: `GoogleService-Info.plist` (place in `ios/Runner/`).  
   - Add Firebase dependencies to `pubspec.yaml` (already included in the project):  
     ```yaml
     firebase_core: ^2.24.2
     firebase_auth: ^4.16.0
     cloud_firestore: ^4.14.0
     firebase_storage: ^11.6.0
     image_picker: ^1.0.7
     google_fonts: ^6.1.0
     ```

3. **Configure Firebase in the App**  
   - Ensure `firebase_core` is initialized in `main.dart` (already set up in the project).  
   - Update `android/build.gradle` and `android/app/build.gradle` with Firebase configurations as per the Firebase setup instructions.

4. **Set Up Emulator or Device**  
   - For Android: Open an emulator in Android Studio or connect a physical device with USB debugging enabled.  
   - For iOS: Use an iOS simulator or connect an iPhone with a developer account configured.

5. **Running the Project**  
   - **Verify Flutter Setup**  
     ```bash
     flutter doctor
     ```
     Ensure no issues are reported (e.g., Flutter, Dart, and connected devices are ready).  
   - **Run the App**  
     Start the app on an emulator or connected device:  
     ```bash
     flutter run
     ```
     This will build and launch the project. Select the target device if prompted.  
   - **Debug Mode**  
     To run in debug mode with hot reload:  
     ```bash
     flutter run --debug
     ```
