# 🌦️ Weather Forecast App

A Python-based desktop application that provides **real-time weather updates** for any city entered by the user. It utilizes the **OpenWeatherMap API** to fetch live weather data and displays it through a clean graphical interface built using **Tkinter** and styled with **ttkbootstrap**.

---

## 🚀 Features

- **Real-Time Weather Updates**  
  Retrieves temperature, weather description, country, and city details.

- **Live Weather Icons**  
  Displays corresponding weather icons using image URLs from OpenWeatherMap.

- **User-Friendly Interface**  
  Built with Tkinter and styled using ttkbootstrap’s modern themes for a polished look.

- **Input Validation**  
  Alerts the user with a popup message if the entered city is not found.

---

## 🛠️ Technologies Used

- Python  
- Tkinter & ttkbootstrap (for GUI)  
- OpenWeatherMap API (for weather data)  
- Pillow (PIL) (for image handling)  
- Requests (for API calls)

---

## 📦 How It Works

1. The user enters a city name in the input field.
2. On clicking the **Search** button, the app sends a request to the OpenWeatherMap API.
3. If the city is valid, the app displays:
   - ✅ City and country name  
   - 🌡️ Current temperature in Celsius  
   - 🌤️ Weather description  
   - 🖼️ Weather icon
4. If the city is not found, an error popup is shown.

---

## 📸 UI Preview

*(Add a screenshot here, e.g., app UI)*  
`![Weather App Screenshot](screenshot.png)`

---

## 📌 Setup Instructions

### 🔁 Clone the Repository

git clone https://github.com/your-username/weather-forecast-app.git

📦 Install Required Libraries
pip install requests pillow ttkbootstrap

▶️ Run the Application
python weather_app.py

🔑 Note: Make sure to replace the API key in the script with your own key from OpenWeatherMap.

🙌 Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
