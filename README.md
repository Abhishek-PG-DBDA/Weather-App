# Weather App

## Overview
This is a **React-based Weather App** that fetches and displays real-time weather data for any city using the **Open-Meteo API**. Users can search for weather information by entering a city name and receive temperature, wind speed, and weather condition details.

## Features
- **City-based weather search**
- Displays **Temperature (°C)**, **Wind Speed (km/h)**, and **Weather Condition** with icons
- Handles **loading state** and **error messages**
- Simple and clean **responsive UI**
- Fully functional in a **browser environment**

## Technologies Used
- **React 18.2.0**
- **ES Modules (ESM.sh)**
- **JavaScript (JSX)**
- **Open-Meteo API** (Weather & Geocoding)
- **CSS Styling**
- **React Hooks (useState, useEffect)**

## How It Works
1. Users enter a **city name** in the input field.
2. The app uses **Open-Meteo Geocoding API** to fetch the city's coordinates.
3. The coordinates are then used to request weather information from **Open-Meteo Weather API**.
4. The weather data, including temperature, wind speed, and condition code, is displayed.
5. The app provides **real-time updates** with proper error handling and loading indicators.

## Running in a Browser
This app works without additional builds. Simply serve the HTML file containing:
```html
<div id="root"></div>
<script type="module" src="weather_app.js"></script>
```

## Demo Link
- [Weather App](https://abhishekprojects-whetherchecker.web.val.run/)
- [Code & Details](https://www.val.town/v/abhishekprojects/WhetherChecker)

## Disclaimer
- This app is for **informational purposes only**.
- Always refer to **official weather services** for critical weather updates.

## License
This project is open-source and free to use.

