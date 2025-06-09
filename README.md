🌦️ Weather Forecast App
This Weather Forecast App is a Python-based desktop application that provides real-time weather updates for any city entered by the user. It utilizes the OpenWeatherMap API to fetch current weather data and displays it in a clean, modern graphical user interface built using Tkinter and styled with ttkbootstrap.

🚀 Features
Real-Time Weather Updates: Retrieves temperature, weather description, country, and city details.

Live Weather Icons: Displays corresponding weather icons using image URLs from OpenWeatherMap.

User-Friendly Interface: Built with Tkinter and styled using ttkbootstrap’s modern themes for a polished look.

Input Validation: Alerts the user with a popup message if the entered city is not found.

🛠️ Technologies Used
Python

Tkinter & ttkbootstrap (for GUI)

OpenWeatherMap API (for weather data)

Pillow (PIL) (for image handling)

Requests (for API calls)

📦 How It Works
The user enters a city name in the input field.

On clicking the Search button, the app sends a request to the OpenWeatherMap API.

If the city is valid, the app displays:

City and country name

Current temperature in Celsius

Weather description

Weather icon

If the city is not found, an error popup is shown.

📌 Setup Instructions

1.Clone the repository:
git clone https://github.com/your-username/weather-forecast-app.git

2.Install required libraries:
pip install requests pillow ttkbootstrap

3.Run the application:
python weather_app.py
