# Reminder App

A Flutter application designed to schedule and manage local reminders with custom titles and times, leveraging local notifications to alert users.

## 🚀 Features

- **Schedule Reminders**: Set reminders for specific dates and times.
- **Custom Titles**: Assign custom titles to each reminder.
- **Local Notifications**: Utilizes `flutter_local_notifications` to deliver timely alerts.
- **Time Zone Support**: Handles time zones for accurate reminder scheduling.
- **User-Friendly Interface**: Simple UI for adding and managing reminders.

## 📁 Project Structure

```
lib/
├── main.dart          # Application entry point, notification initialization
├── models/            # Data models for reminders
├── screens/           # UI for reminder list and adding/editing reminders
├── services/          # Notification scheduling and management logic
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
   cd reminder_app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```

### Platform-Specific Setup for Local Notifications

**Android:**
- Ensure your `AndroidManifest.xml` includes necessary permissions and configurations for notifications.

**iOS:**
- Ensure your `Info.plist` includes necessary permissions for notifications.
- You might need to enable Push Notifications capability in Xcode.

## 🏃 Usage

To run the app, use the following command:
```sh
flutter run
```

Once the app is running, you can:
- Add new reminders by specifying a title, date, and time.
- View your scheduled reminders.
- Receive local notifications at the set times.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications) - For scheduling and displaying local notifications
- [timezone](https://pub.dev/packages/timezone) - For accurate time zone handling
- [intl](https://pub.dev/packages/intl) - For internationalization and date/time formatting
- [flutter_timezone](https://pub.dev/packages/flutter_timezone) - For getting the device's current time zone
- [device_info_plus](https://pub.dev/packages/device_info_plus) - For retrieving device information (potentially for platform-specific notification handling)

## 📝 License

This project is open source and available under the MIT License.