Weather App 🌤️

This Weather App is a simple and intuitive application that allows users to view real-time weather details for any city or their current location. Built using HTML, CSS, and JavaScript, the app fetches live weather data through API integration and provides information such as humidity, wind speed, and cloud conditions.

🚀 Live Demo
Check out the live demo of the project:
Weather App Live Demo (Replace # with your live link once hosted)

✨ Features
Search by City: Enter any city name to fetch and display weather details.
Current Location Weather: Use geolocation to automatically retrieve weather data for your current location.
Weather Insights: Displays humidity, wind speed, and cloud data.
Responsive Design: Works seamlessly across devices.

⚙️ How It Works
City Input Search:
Enter the name of a city in the input field.
Click on the search button to fetch weather details for the specified city.
Current Location:
Click on the "Use My Location" button to allow the app to access your location.
The app fetches weather details for your current latitude and longitude.
Data Display:
The app uses the weather API to display:
Humidity (%)
Wind speed (km/h or mph)
Cloud conditions (Clear, Partly Cloudy, etc.)

🛠️ Tools and Technologies
HTML: Structure of the application.
CSS: Styling for a clean and user-friendly interface.
JavaScript: Logic to fetch and display weather data.
Weather API: Provides real-time weather information.
Geolocation API: Retrieves user's current location.

🧠 Approach and Challenges
Approach
Set up the structure using HTML and styled it with CSS for a minimalistic design.
Integrated the Weather API to fetch live weather data using JavaScript's Fetch API.
Used the Geolocation API to get the user's current position and retrieve weather data for that location.
Challenges Faced & Solutions
Handling API Errors:
Challenge: The API occasionally returned errors for invalid city names or network issues.
Solution: Added error handling with appropriate user feedback for invalid inputs or server issues.
Geolocation Permissions:
Challenge: Users denying location access caused the app to fail.
Solution: Implemented a fallback message to notify users about the need for location permissions.
Cross-Origin Requests:
Challenge: Encountered CORS issues during API integration.
Solution: Configured headers in API requests and used browser-friendly services.

🚀 Future Improvements
Detailed Forecast:
Add a 5-day weather forecast feature for cities and current location.
Enhanced UI:
Improve the design for better user experience, including animations and themes.
Multiple Language Support:
Provide weather details in different languages for wider usability.
Temperature Units:
Allow users to toggle between Celsius and Fahrenheit.
Mobile Optimization:
Optimize the app further for mobile-first design.
