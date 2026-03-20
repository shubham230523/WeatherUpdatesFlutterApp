# WeatherUpdatesFlutterApp 🌤️

A feature-rich, real-time Weather Forecasting application built with **Flutter**. This app provides users with accurate weather data based on their current GPS location or a specific city search, featuring a polished UI with smooth animations.

---

## 🌟 Features

* **Auto-Location Detection:** Automatically fetches and displays the weather for your current device location using the `geolocator`.
* **City Search:** Allows users to manually input any city name to check current weather conditions globally.
* **Data Persistence:** Remembers the last searched city using `shared_preferences`, so the app opens with relevant data even after being closed.
* **Real-time API Integration:** Powered by the **OpenWeatherMap API** for precise temperature, humidity, wind speed, and weather descriptions.
* **Dynamic UI & Animations:** * Responsive design that adjusts based on weather conditions.
    * Beautiful weather-themed animations using **Lottie**.
    * Custom animated splash screen on startup.
* **Offline Support:** Caches the last retrieved weather data to provide information even when internet connectivity is lost.

---

## 🛠 Tech Stack

| Category | Technology / Package |
| :--- | :--- |
| **Framework** | Flutter (Dart) |
| **API** | OpenWeatherMap API |
| **Networking** | `http` |
| **Location** | `geolocator`, `geocoding` |
| **Local Storage** | `shared_preferences` |
| **Animations** | `lottie`, `animated_splash_screen` |
| **Formatting** | `intl` (Date/Time formatting) |

---

## 🏗 Project Structure

```text
lib/
├── models/      # Data models for Weather and Forecast
├── services/    # API calling and Location services
├── screens/     # UI Screens (Home, Search, Splash)
├── widgets/     # Reusable UI components
└── main.dart    # Application entry point
````

-----

## 🚀 Getting Started

### Prerequisites

  * [Flutter SDK](https://docs.flutter.dev/get-started/install) installed.
  * An API Key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation & Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/shubham230523/WeatherUpdatesFlutterApp.git
    ```
2.  **Install dependencies:**
    ```bash
    flutter pub get
    ```
3.  **Add your API Key:**
    Open `lib/services/weather_service.dart` (or your constants file) and replace the placeholder with your OpenWeatherMap API key.

4.  **Run the app:**
    ```bash
    flutter run
    ```

-----
