# Firebase Login App

A Flutter project that integrates Firebase Authentication to allow users to log in and register with email and password, and display user information.

## 🚀 Features

- **User Authentication**: Secure login and registration using email and password.
- **Firebase Integration**: Utilizes Firebase Core and Firebase Auth for backend services.
- **Auth State Management**: Uses `StreamBuilder` to reactively manage and display authentication states.
- **User Information Display**: Shows relevant user details upon successful login.

## 📁 Project Structure

```
lib/
  ├── main.dart          # Application entry point and Firebase initialization
  ├── screens/           # UI for login, registration, and home screens
  │   ├── login_screen.dart
  │   ├── register_screen.dart
  │   └── home_screen.dart
  └── services/          # Authentication services (e.g., firebase_auth_service.dart)
```

## 🛠️ Getting Started

This project is a starting point for a Flutter application that demonstrates Firebase Authentication.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Prerequisites

- Flutter SDK
- Dart SDK
- Any IDE with Flutter support (VS Code, Android Studio, etc.)
- A Firebase Project configured with Email/Password Authentication enabled.

### Installation

1. Clone this repository.
2. Navigate to the project directory:
   ```sh
   cd firebase_login
   ```
3. Install FlutterFire CLI (if not already installed):
   ```bash
   dart pub global activate flutterfire_cli
   ```
   If `flutterfire` command is not found, add it to your PATH:
   ```bash
   export PATH="$PATH:$HOME/.pub-cache/bin"
   ```
4. Configure your Flutter project with Firebase:
   ```bash
   flutterfire configure --project=<YOUR_FIREBASE_PROJECT_ID>
   ```
   (Replace `<YOUR_FIREBASE_PROJECT_ID>` with your actual Firebase project ID).
   This will generate `lib/firebase_options.dart`.
5. Install dependencies:
   ```sh
   flutter pub get
   ```

## 🏃 Usage

To run the app, use the following command:
```sh
flutter run
```

Upon launching the app, you will be presented with a login screen. You can:
- **Register**: Create a new account using an email and password.
- **Login**: Use existing credentials to access the home screen, which will display user information.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [Firebase Core](https://pub.dev/packages/firebase_core) - Firebase initialization
- [Firebase Auth](https://pub.dev/packages/firebase_auth) - Firebase Authentication services

## 📝 License

This project is open source and available under the MIT License.