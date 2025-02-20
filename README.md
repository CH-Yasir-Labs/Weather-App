# Weather-App


This PyQt5 Weather App is a simple yet effective GUI-based application that allows users to check the weather of any city using the OpenWeather API. It fetches real-time temperature, weather conditions, and an emoji representation of the weather.

1. Features
✅ User Input: The user enters a city name to retrieve weather data.
✅ API Request Handling: Sends a request to the OpenWeather API and handles all potential errors.
✅ Weather Display: Shows:

Temperature in Fahrenheit
Weather description (e.g., "clear sky", "rainy")
Emoji representation of the weather
✅ Modern GUI with PyQt5: A neatly styled interface with centered labels and stylish fonts.
✅ Comprehensive Error Handling: Handles common HTTP errors (e.g., 404 City not found, 500 Server error, 403 Forbidden, 400 Bad Request).
✅ Custom Weather Icons (Emojis): Displays different emojis based on the weather condition.
✅ Responsive UI: Uses QVBoxLayout for a clean, vertically stacked design.
2. How It Works
User enters a city name into a text box.
Clicking the "Get Weather" button triggers an API request to OpenWeather.
The app fetches weather data, extracts the temperature, weather description, and weather condition ID.
The temperature is converted from Kelvin to Fahrenheit.
The app displays the temperature, weather emoji, and description in a well-styled UI.
If an error occurs (e.g., city not found, network issues), a detailed error message is displayed.
