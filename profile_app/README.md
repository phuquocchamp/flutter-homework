# Personal Profile App

A Flutter application designed to display personal information, including a profile picture, personal details (name, title, bio), a list of skills with progress bars, social media links, and a Dark Mode/Light Mode toggle.

## 🚀 Features

- **Responsive UI**: The interface automatically adjusts to different screen sizes.
- **Dark Mode Toggle**: Seamlessly switch between light and dark themes.
- **Personal Information Display**: Showcases name, title, and a brief biography.
- **Skills Section**: Displays a list of skills with visual progress indicators.
- **Social Media Links**: Provides clickable links to social media profiles.
- **State Management**: Utilizes Provider for efficient state management.
- **Material Design 3**: Implements a modern UI with Material Design 3 principles.

## 📁 Project Structure

```
lib/
├── main.dart                           # Entry point, dependency injection
├── core/                               # Core functionality
│   ├── constants/                      # App-wide constants
│   └── theme/                          # Theme configuration and state management
└── features/
    └── profile/                        # Profile feature module
        ├── data/                       # Data layer (datasources, models, repositories)
        ├── domain/                     # Domain layer (entities, repositories, usecases)
        └── presentation/               # Presentation layer (pages, providers, widgets)
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
   cd profile_app
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
- View the personal profile information.
- Toggle between Dark Mode and Light Mode using the dedicated button.
- Click on social media icons to open the respective links.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [Provider](https://pub.dev/packages/provider) - State management
- [url_launcher](https://pub.dev/packages/url_launcher) - For launching URLs (social links)
- [equatable](https://pub.dev/packages/equatable) - For value equality in models

## 📝 License

This project is open source and available under the MIT License.