# Expense Tracker App

A comprehensive offline expense tracking application built with Flutter and Dart, featuring local data persistence, beautiful charts, and support for light/dark themes.

## 🚀 Features

- **Add, Edit, Delete Expenses**: Manage your expense records with ease.
- **View Expenses**: Organized list view of all your transactions.
- **Analytics & Visualization**: Pie charts and summaries of spending by category.
- **Local Storage**: All data stored locally using the Hive database.
- **Responsive Design**: Adaptive UI for various screen sizes.
- **Dark/Light Mode**: Supports beautiful Material Design 3 themes.

## 📁 Project Structure

```
lib/
├── main.dart                          # App entry point, Hive initialization
├── models/                            # Data models (e.g., expense.dart)
├── providers/                         # State management with ChangeNotifier
├── screens/                           # App screens (e.g., home_screen.dart)
├── widgets/                           # Reusable components (e.g., expense_chart.dart)
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
   cd expense_tracker
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Generate Hive adapters:
   ```sh
   flutter pub run build_runner build --delete-conflicting-outputs
   ```

## 🏃 Usage

To run the app, use the following command:
```sh
flutter run
```

### Key Interactions:
- **Adding an Expense**: Tap the `+` button, fill in details (title, amount, category, date), and save.
- **Viewing & Editing**: Expenses are listed chronologically. Tap the menu icon on an expense card to edit or delete.
- **Analytics**: Switch to the Analytics tab to view spending summaries and pie charts by category.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [Provider](https://pub.dev/packages/provider) - State management
- [Hive](https://docs.hivedb.dev/) - Local database
- [fl_chart](https://pub.dev/packages/fl_chart) - Charts for data visualization
- [intl](https://pub.dev/packages/intl) - Date formatting
- [uuid](https://pub.dev/packages/uuid) - Unique ID generation

## 📝 License

This project is licensed under the MIT License.