# News Reader App

A Flutter-based mobile application for reading news articles from various sources.

## 🚀 Features

- **Browse Articles**: View the latest news articles.
- **Category Filtering**: Filter news by different categories.
- **Search Functionality**: Search for specific news topics.
- **Bookmark Articles**: Save favorite articles for later reading.
- **User Interface**: Clean and intuitive design.
- **Theme Support**: Dark and Light theme options.

## 📁 Project Structure

```
lib/
├── models/         # Data models for news articles, categories, etc.
├── screens/        # UI screens (e.g., home, article detail, search, bookmarks)
├── services/       # API integration and data fetching logic
├── widgets/        # Reusable UI components
└── main.dart       # Application entry point
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

- Flutter SDK (>=3.2.0)
- Dart SDK (>=3.2.0)
- Android Studio / VS Code with Flutter extension

### Installation

1. Clone this repository.
2. Navigate to the project directory:
   ```sh
   cd news_reader_app
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
- Browse the latest news on the home screen.
- Use the category filters to narrow down news topics.
- Search for specific articles using the search bar.
- Bookmark articles to read them later.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [http](https://pub.dev/packages/http) - For making HTTP requests to news APIs
- [url_launcher](https://pub.dev/packages/url_launcher) - For launching URLs (e.g., opening articles in a browser)
- [intl](https://pub.dev/packages/intl) - For internationalization and date formatting
- [cached_network_image](https://pub.dev/packages/cached_network_image) - For caching and displaying network images

## 📝 License

This project is licensed under the MIT License.