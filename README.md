# Weather App

This is a simple and responsive weather application built using HTML, CSS, and JavaScript. It fetches real-time weather data from the OpenWeatherMap API and displays key weather information for any searched city.

## Features

- Search weather by city name
- Displays:
  - Current temperature
  - Weather forecast (Clear, Rain, etc.)
  - Minimum and maximum temperature
  - Feels-like temperature
  - Humidity
  - Wind speed
  - Pressure
  - Country name and local time
- Responsive design for desktop and mobile devices

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Enter a city name in the search bar and press Enter or click the search icon.
4. The application will fetch and display the current weather for the entered city.

## API Key

This app uses the OpenWeatherMap API. You need to sign up at [https://openweathermap.org/](https://openweathermap.org/) to get your free API key and replace the placeholder in the JavaScript file if needed:
```javascript
const weatherUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&APPID=YOUR_API_KEY`;
```
