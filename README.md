# WeatherWeb

WeatherWeb is a user-friendly web application that provides real-time weather information. The app automatically detects your location or allows you to manually search for the weather conditions in different places. It utilizes the OpenWeather API to fetch accurate and up-to-date weather data.

## Features

- **Automatic Location Detection:** The app prompts you to allow location access for automatic weather updates based on your current location.
- **Manual Location Search:** You can manually search for the weather conditions in other places by entering the city name in the search bar.
- **Detailed Weather Information:** View detailed information, including temperature, humidity, wind speed, and more.
- **Responsive Design:** The app is designed to work seamlessly on both desktop and mobile devices.

## Screenshots

![](https://i.imgur.com/g8CeiFW.png)

## Getting Started

Follow these steps to run the WeatherApp locally:

1. Clone the repository:

     git clone https://github.com/erindrade/WeatherApp.git

2.Navigate to the project directory:

   cd WeatherApp
   
   Open index.html in your preferred web browser.


Automatic Location Detection
When you open the app, your browser will request access to your location. Allow the app to access your location for automatic weather updates.


Manual Location Search
If you want to check the weather for a different location, use the search bar. Enter the name of the city, and the app will fetch the weather information for that location.

Technologies Used
HTML
CSS
JavaScript (ES6+)
OpenWeather API


API Key
This project uses the OpenWeather API to fetch weather data. Make sure to replace the placeholder API key in the main.js file with your own key. You can obtain a free API key by signing up on the OpenWeather website.

// main.js
const apiKey = 'your_openweather_api_key';


Acknowledgments
Weather icons by Icons8
