# Weather App

A smart Flutter weather application that allows users to view weather information based on their current GPS location or search by city name with intelligent autocomplete functionality.

## 🚀 Features

- **GPS-Based Weather**: Automatically fetches weather data for the current location.
- **City Search with Autocomplete**: Smart search functionality for cities, similar to Google Maps.
- **5-Day Forecast**: Displays weather predictions for the next five days with a horizontal scroll.
- **Detailed Weather Information**: Shows temperature, description, coordinates, and last updated time.
- **Real-time Refresh**: Reload weather data with a dedicated refresh button.
- **Environment Variables**: Secure API key management using `.env` files.

## 📁 Project Structure

```
lib/
├── main.dart                     # Entry point, dependency injection
├── models/                       # Data models for weather and forecast
├── services/                     # API integration and location services
├── screens/                      # UI for current weather, forecast, and search
└── widgets/                      # Reusable UI components (e.g., weather icons)
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
- **OpenWeatherMap API Key**: Obtain a free API key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation

1. Clone this repository.
2. Navigate to the project directory:
   ```sh
   cd weather_app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. **Configure OpenWeatherMap API Key**:
   - Copy the `.env.example` file to `.env`:
     ```sh
     cp .env.example .env
     ```
   - Open the newly created `.env` file and replace `YOUR_API_KEY_HERE` with your actual OpenWeatherMap API key:
     ```
     OPENWEATHER_API_KEY=your_actual_api_key_here
     ```

## 🏃 Usage

To run the app, use the following command:
```sh
flutter run
```

Once the app is running, you can:
- Allow location permissions to see weather for your current location.
- Use the search bar to find weather for other cities.
- View the 5-day forecast by scrolling horizontally.
- Tap the refresh button to get the latest weather data.

## 🏗️ Built With

- [Flutter](https://flutter.dev/) - UI toolkit
- [Dart](https://dart.dev/) - Programming language
- [geolocator](https://pub.dev/packages/geolocator) - For GPS location services
- [http](https://pub.dev/packages/http) - For making HTTP requests to OpenWeatherMap API
- [flutter_dotenv](https://pub.dev/packages/flutter_dotenv) - For managing environment variables (API key)
- [flutter_typeahead](https://pub.dev/packages/flutter_typeahead) - For autocomplete search suggestions

## 📝 License

This project is open source and available under the MIT License.
