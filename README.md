# Weather App

A simple weather application that displays current weather data for a city entered by the user. The app uses the OpenWeatherMap API to fetch weather information such as temperature, humidity, wind speed, and the weather condition icon.

## Features

- Fetches current weather data using the OpenWeatherMap API.
- Displays temperature, humidity, and wind speed.
- Updates dynamically with city search.
- Displays appropriate weather icons based on weather conditions (Clouds, Clear, Rain, Drizzle, Mist).
- Shows an error message if the city is not found.

## Project Structure

```bash
└── Weather-App
    ├── .env
    ├── index.html
    ├── eslint.config.js
    ├── public
    ├── images
    ├── package.json
    ├── vite.config.js
    ├── README.md
    └── src
        ├── App.jsx
        ├── index.css
        ├── assets
        ├── components
        │   ├── Weather2.css
        │   └── Weather.jsx
        └── main.jsx

```

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```

2. Open the project directory:
    ```bash
    cd weather-app
    ```

3. Open the `index.html` file in your browser to use the app.

## API Key Setup

This project uses the OpenWeatherMap API. You will need to replace the `apiKey` in `script.js` with your own API key.

1. Get your API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Replace the `apiKey` variable in `script.js`:
    ```javascript
    const apiKey = "YOUR_API_KEY";
    ```
