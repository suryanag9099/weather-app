# Weather App

## Overview
This Weather App is a React-based application that provides real-time weather forecasts using the Open-Meteo API. The app allows users to search for any city and view hourly and daily weather forecasts with key weather parameters like temperature, humidity, wind speed, and visibility.

## Features
- **Search for any city**: Autocomplete search with location suggestions using OpenStreetMap's Nominatim API.
- **Current Weather**: Displays real-time temperature, weather condition, visibility, humidity, and wind speed.
- **Hourly Forecast**: Highlights the closest upcoming time frame with relevant weather conditions.
- **Daily Forecast**: Provides weather conditions for multiple days ahead.
- **User-friendly UI**: Interactive and visually appealing UI with components like cards and icons.

## Tech Stack
- **Frontend**: React, JavaScript, HTML, CSS
- **API**: Open-Meteo API (for weather data), OpenStreetMap API (for location search)
- **State Management**: React Hooks (useState, useEffect)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/weather-app.git
   cd weather-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
4. Open the app in your browser at `http://localhost:3000`.

## Project Structure
```
/weather-app
│── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── DefaultScreen.js
│   │   ├── SearchResult.js
│   ├── ui/
│   │   ├── CardLayout.js
│   ├── utils/
│   │   ├── weatherCodesMapping.js
│   ├── assets/
│   │   ├── images/
│   ├── style/
│   │   ├── index.css
│   ├── App.js
│   ├── index.js
│── package.json
│── README.md
```

## API Usage
- **Weather Data**: Retrieved using Open-Meteo's API.
- **Location Suggestions**: Fetched using OpenStreetMap's Nominatim API.

## How It Works
1. **Default Screen**: Displays weather data for New Delhi by default.
2. **Search Feature**: Users can search for a city, triggering API calls to fetch and display weather data.
3. **Weather Display**: The app dynamically updates and presents hourly and daily weather forecasts in a user-friendly layout.

## Future Enhancements
- Add weather alerts for severe conditions.
- Implement dark mode for better UI experience.
- Optimize performance by caching previous searches.


