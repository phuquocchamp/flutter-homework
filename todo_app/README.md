# Todo App - Clean Architecture

A Flutter Todo application built with Clean Architecture principles, allowing users to manage their task list with full offline storage capabilities.

## 🚀 Features

- **Task Management**: Add new tasks with titles and descriptions, mark tasks as complete, and delete tasks with confirmation.
- **Automatic Sorting**: Uncompleted tasks are automatically prioritized and displayed first.
- **Statistics**: View total tasks, pending tasks, completed tasks, and completion percentage.
- **Offline Storage**: All data is automatically saved to local storage using `shared_preferences`, ensuring data persistence without an internet connection.
- **User Interface**: Modern UI with Material Design 3, automatic Dark Mode, responsive layout, and smooth animations.
- **Clean Architecture**: Organized codebase following SOLID principles for maintainability and scalability.

## 📁 Project Structure

```
lib/
├── main.dart                     # Entry point
├── core/                         # Shared utilities (constants, theme, utils)
├── domain/                       # Business logic (entities, repositories, usecases)
├── data/                         # Data layer (models, datasources, repositories)
└── presentation/                 # UI layer (pages, widgets, state)
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
   cd todo_app
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
- Add new tasks using the input field.
- Mark tasks as complete by tapping on them.
- Delete tasks by swiping or using a delete button.
- View task statistics on the main screen.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [shared_preferences](https://pub.dev/packages/shared_preferences) - For local data storage

## 📝 License

This project is open source and available under the MIT License.