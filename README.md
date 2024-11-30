# 🌤️ Weather App

A **React** application that fetches and displays real-time weather data using the [OpenWeatherMap API](https://openweathermap.org/current). Search for any city to view the temperature, humidity, wind speed, and weather condition with a matching icon.

---

## ✨ Features
- 🌎 **Search by city**: Enter a city name to fetch its current weather.
- 🌡️ **Temperature in Celsius**: Displays the current temperature.
- 💨 **Wind speed**: Shows the wind speed in km/h.
- 💧 **Humidity**: Displays the current humidity percentage.
- 🖼️ **Weather icons**: Icons change based on weather conditions (e.g., sunny, cloudy, rainy).

---

## 🛠️ Installation and Setup

### 1️⃣ Clone the repository

git clone <your-repository-url>

Install dependencies
Install the required Node.js packages using npm:

npm install

Add your API key

Sign up for a free API key at OpenWeatherMap.
Create a .env file in the root of the project and add the following line:
makefile
Copy code
VITE_APP_ID=your-api-key-here

Run the application
Start the development server with:

npm run dev
The app will run at http://localhost:5173.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
