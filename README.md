# 🌦️ Weather App

A sleek and modern Flutter app that provides real-time weather information based on your location or a city of your choice. Built with Flutter and integrated with the OpenWeatherMap API.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

---

## ✨ Features

- 📍 Fetch weather by current location
- 🏙️ Search weather by city name
- 🌡️ Displays temperature, humidity, wind speed, and weather conditions
- 🌈 Dynamic UI with weather-based visuals
- 📱 Responsive and minimal design

---

## 🛠️ Getting Started

### Prerequisites
- Flutter SDK
- Dart
- A code editor like VS Code or Android Studio
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/VipranshOjha/Weather-App.git
   cd Weather-App
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Add your API key**

   - Get your API key from [OpenWeatherMap](https://openweathermap.org/api)
   - Replace the placeholder in the API config file (e.g., `api_service.dart`) with your key:
     ```dart
     const String apiKey = 'YOUR_API_KEY_HERE';
     ```

4. **Run the app**
   ```bash
   flutter run
   ```

---

## 📁 Project Structure

```
lib/
├── main.dart
├── screens/
│   ├── home_screen.dart
│   └── search_screen.dart
├── services/
│   └── weather_service.dart
├── models/
│   └── weather_model.dart
└── widgets/
    └── weather_card.dart
```

---

## 🚧 Future Improvements

- [ ] Add hourly and weekly forecasts
- [ ] Include more detailed weather metrics (UV Index, Air Quality, etc.)
- [ ] Cache data for offline access
- [ ] Add animations for transitions and weather effects
- [ ] Support for multiple languages

---

## 🙋‍♂️ Author

**Vipransh Ojha**  
[GitHub](https://github.com/VipranshOjha)

---
