# Note App

A simple note-taking application built with Flutter, utilizing Provider for state management, allowing users to easily create, edit, and delete notes.

## 🚀 Features

- **Create Notes**: Add new notes with a title and content.
- **Edit Notes**: Modify existing note entries.
- **Delete Notes**: Remove notes with a confirmation prompt.
- **Refresh Notes**: Easily refresh the list of notes.
- **State Management**: Implemented with Provider for efficient state handling.

## 📁 Project Structure

```
lib/
├── main.dart          # Application entry point
├── models/            # Data models for notes
├── providers/         # State management logic (e.g., NoteProvider)
├── screens/           # UI screens (e.g., home screen, note editor)
└── widgets/           # Reusable UI components
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
- Dart SDK
- Android Studio / VS Code with Flutter extension

### Installation

1. Clone this repository.
2. Navigate to the project directory:
   ```sh
   cd notes_app
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

Once the app is running, you can:
- Tap the `+` button to create a new note.
- Tap on an existing note to edit its title or content.
- Swipe a note to delete it (or use a dedicated delete button if implemented).

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [Provider](https://pub.dev/packages/provider) - State management

## 📝 License

This project is open source and available under the MIT License.