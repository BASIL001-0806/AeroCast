# 🌦 Weather Dashboard

A modern and responsive Weather Dashboard web application that provides real-time weather information for any city using a public weather API.

---

## 🚀 Features

* 🔍 **City Search** – Search weather by city name instantly
* 🌡 **Real-Time Data** – Displays current temperature, humidity, and wind speed
* 🌤 **Weather Conditions** – Shows overall weather status (e.g., Clear, Rainy, Cloudy)
* 📅 **Forecast** – Provides short-term weather forecast
* 📱 **Responsive Design** – Works smoothly on desktop and mobile devices
* 🎨 **Clean UI** – Simple, user-friendly interface

---

## 🛠 Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling & responsiveness
* **JavaScript (Vanilla JS)** – Logic & API handling
* **Weather API** – For fetching real-time data (e.g., OpenWeather API)

---

## 📦 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/weather-dashboard.git
   ```

2. **Navigate to the project folder**

   ```bash
   cd weather-dashboard
   ```

3. **Open the project**

   * Simply open `index.html` in your browser

---

## 🔑 API Configuration

1. Get your free API key from a weather provider (e.g., OpenWeather)
2. Add your API key inside your JavaScript file:

   ```javascript
   const API_KEY = "your_api_key_here";
   ```

⚠️ *Important:* Do not expose your API key in public repositories. Use `.env` for advanced setups.

---

## 📂 Project Structure

```
weather-dashboard/
│
├── index.html        # Main HTML file
├── style.css         # Stylesheet
├── script.js         # JavaScript logic
├── assets/           # Images/icons
├── README.md         # Project documentation
└── .gitignore
```

---

## 📸 Screenshots

*(Add your project screenshots here for better presentation)*

---

## ⚙️ Functionality Overview

* Fetches weather data using API
* Displays:

  * Temperature
  * Humidity
  * Wind Speed
  * Weather Condition
* Updates UI dynamically based on user input
* Handles invalid city names gracefully

---

## 🔮 Future Improvements

* 🌙 Dark mode toggle
* 📍 Auto-detect current location weather
* 💾 Save recent searches (Local Storage)
* 🎬 Loading animations & better UI effects
