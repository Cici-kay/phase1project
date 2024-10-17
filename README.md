Weather App

Welcome to the Weather App! 
This application allows you to search for any city and view the current weather conditions, including temperature, humidity, wind speed, and more.

Features

City Search: Enter any city name to retrieve its weather data.

Detailed Weather Information: View temperature (in Celsius), humidity, wind speed, pressure, visibility, sunrise, and sunset times.
Weather Alerts: Receive alerts for various temperature ranges.
Responsive Design: The app is styled to work seamlessly on both desktop and mobile devices.
Technologies Used
HTML: Structure of the web application.
CSS: Styling and layout of the application.
JavaScript: Fetching weather data from an API and updating the UI.
Open Weather API: Source of real-time weather data.
Getting Started
To run the application locally, follow these steps:

Clone the repository:

bash
Copy code
git clone <repository-url>
cd weather-app
Open index.html in your browser.

Enter a city name in the search box and click the Search button.

Code Overview
HTML Structure
The main HTML structure is contained in index.html, which includes:

Input field for city name.
Display sections for weather data, including temperature, humidity, wind speed, etc.
Style link for CSS and script link for JavaScript.
CSS Styling
The styles are defined in style.css, featuring:

A dark theme with a background image.
Flexbox layout for responsive design.
Custom styles for various weather indicators and components.
JavaScript Functionality
The JavaScript logic is contained in app.js, which includes:

Event listener for the search button.
Function getWeather() to fetch data from the Open Weather API.
Function displayWeather(data) to update the UI with the fetched data.
API Configuration
Make sure to replace the API key in the code with your own. You can sign up at RapidAPI to obtain a free key for the Open Weather API.

javascript
Copy code
const options = {
    method: "GET",
    headers: {
        "x-rapidapi-key": "YOUR_API_KEY_HERE",
        "x-rapidapi-host": "open-weather13.p.rapidapi.com",
    },
};
License
This project is licensed under the MIT License. Feel free to modify and use it as you wish!

Contact
For any inquiries or feedback, please reach out to the author at [your-email@example.com].

Enjoy exploring the weather!



