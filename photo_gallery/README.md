# Photo Gallery App

A beautiful and feature-rich photo gallery application built with Flutter and Dart. It allows users to capture photos with the device camera, select photos from the gallery, and manage them with ease. All photos are stored locally on the device with a responsive grid layout and fullscreen viewing experience.

## 🚀 Features

- **Capture Photos**: Take new photos using the device camera.
- **Select Photos**: Pick single or multiple photos from the device gallery.
- **View Photos**: Display photos in a responsive grid layout.
- **Fullscreen View**: View photos in fullscreen with interactive zoom and pan.
- **Delete Photos**: Remove individual photos or perform batch deletions.
- **Local Storage**: All photos are stored locally on the device.
- **Responsive Design**: Adaptive UI for different screen sizes.
- **Dark/Light Mode**: Supports Material Design 3 themes.

## 📁 Project Structure

```
lib/
├── main.dart                          # App entry point
├── models/                            # Data models (e.g., photo.dart)
├── providers/                         # State management with ChangeNotifier (e.g., PhotoProvider)
├── screens/                           # UI screens (e.g., home_screen.dart, fullscreen_photo_screen.dart)
├── utils/                             # Utility functions (e.g., storage_util.dart, permission_util.dart)
└── theme/                             # Theme definitions
```

## 🛠️ Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Prerequisites

- Flutter SDK (3.9.2 or newer)
- Dart SDK (included with Flutter)
- Android Studio, Xcode, or VS Code with Flutter extension

### Installation

1. Clone this repository.
2. Navigate to the project directory:
   ```sh
   cd photo_gallery
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```

## 🏃 Usage

To run the app, use the following command:
```sh
flutter run
```

### Key Interactions:
- **Taking a Photo**: Tap the camera icon to capture a new photo.
- **Selecting Photos**: Tap the gallery icon to pick photos from your device's gallery.
- **Viewing Photos**: Tap any photo in the grid to view it in fullscreen. Pinch to zoom and drag to pan.
- **Deleting Photos**: Long-press a photo to enter selection mode, then select photos and tap the delete icon.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [Provider](https://pub.dev/packages/provider) - State management
- [image_picker](https://pub.dev/packages/image_picker) - Camera and gallery access
- [permission_handler](https://pub.dev/packages/permission_handler) - Runtime permission requests
- [path_provider](https://pub.dev/packages/path_provider) - Access app storage directory
- [shared_preferences](https://pub.dev/packages/shared_preferences) - Store metadata
- [intl](https://pub.dev/packages/intl) - Date formatting
- [uuid](https://pub.dev/packages/uuid) - Unique identifier generation

## 📝 License

This project is licensed under the MIT License.