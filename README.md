# PRODIGY_WD_05
A Weather web application that fetches weather data from a weather API based on the user's location or an inputted location. The app displays the current weather conditions, temperature, humidity, and other relevant information, providing users with a clear and responsive interface.

Features :
Location-Based Weather: Fetches the weather based on the user's current location using geolocation.
Search Functionality: Allows users to enter a city name to retrieve weather data for that location.
Weather Details: Displays key weather information such as temperature, humidity, wind speed, and weather conditions.

Technologies Used :
HTML: For structuring the user interface.
CSS: For styling the web page and ensuring responsiveness.
JavaScript: For fetching weather data from the API and handling user interactions.
Weather API: Used to fetch live weather data.

How to Use ?
1.Clone the Repository:
git clone https://github.com/your-username/weather-app.git

2.Open the project: Navigate to the folder and open index.html in your browser.
cd weather-app
open index.html

Usage:
Location-Based Weather: Upon loading, the app will request permission to access the user’s location to show the weather for that location.
Manual Search: Users can enter a city name in the search bar to get the weather for that city.

Setup Instructions :
1.Sign up for a free API key at OpenWeatherMap or any weather API provider.
2.Replace the placeholder API key in script.js with your API key:
const apiKey = 'your-api-key';

