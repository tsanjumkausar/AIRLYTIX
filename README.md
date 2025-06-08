# AIRLYTIX

AIRLYTIX is a web application that allows users to check the air quality and pollution levels for any location worldwide. Users can search by city name or enter latitude and longitude coordinates to get real-time air quality data, including the Air Quality Index (AQI) and concentrations of various pollutants.

## Features

- Search air quality by city name (with optional state for USA).
- Search air quality by latitude and longitude coordinates.
- Automatic detection of user's current location to display local air quality.
- Displays Air Quality Index (AQI) with status indicators (Good, Fair, Moderate, Poor, Very Poor).
- Shows concentrations of key air pollutants including Carbon Monoxide, Nitrogen Monoxide, Nitrogen Dioxide, Ozone, Sulphur Dioxide, Fine 
  Particulate Matter (PM2.5), Coarse Particulate Matter (PM10), and Ammonia.
- Interactive UI with search hints and modal display of results.

## How to Use

1. Open the `index.html` file in a modern web browser.
2. Enter a city name in the input box, optionally including the state (for USA), or enter latitude and longitude coordinates.
3. Click the "Search" button to fetch and display the air quality data.
4. Alternatively, allow the app to access your location to automatically get local air quality information.
5. View the Air Quality Index and pollutant concentrations in the popup modal.

## Technologies Used

- HTML5, CSS3 for the user interface.
- JavaScript (ES6 modules) for application logic.
- OpenWeatherMap Air Pollution API for real-time air quality data.
- Geocoding API from OpenWeatherMap for location search.
- Browser Geolocation API for detecting user location.

## Project Structure

- `index.html` - Main HTML page.
- `style.css` - Stylesheet for the app.
- `script.js` - Main JavaScript logic for fetching and displaying air quality data.
- `countries.js` - Module containing country codes and names for display purposes.
- `bgImage.png`, `bgImage1.jpg` - Background images used in the UI.

## License

This project is open source and available under the MIT License.


