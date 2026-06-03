# 🌤️ Weather App

> A responsive weather application built with vanilla JavaScript that delivers real-time weather data for any city worldwide or your current location, powered by the OpenWeatherMap API.

---

## 📌 Overview

A clean, browser-based weather application with zero dependencies — no frameworks, no libraries. Built using core HTML, CSS, and JavaScript, it fetches live weather data via the OpenWeatherMap API and displays it in a user-friendly interface.

---

## ✨ Features

- 🔍 **City Search** — Enter any city name to get instant weather data
- 📍 **Current Location Detection** — Fetches weather based on your live GPS coordinates via the browser Geolocation API
- 🌡️ **Weather Details** — Displays temperature, weather condition, humidity, and wind speed
- 🎨 **Responsive UI** — Clean layout that works across devices

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Structure and layout |
| **CSS3** | Styling and responsiveness |
| **JavaScript (Vanilla)** | API calls, DOM manipulation, geolocation |
| **OpenWeatherMap API** | Live weather data source |

---

## 📁 Project Structure

```
Weather-app/
│
├── index.html       # Main HTML structure
├── style.css        # Styling and layout
├── script.js        # Core logic — API calls, geolocation, DOM updates
└── README.md
```

---

## ⚙️ Setup & Run

### Prerequisites
- A free OpenWeatherMap API key → [Get one here](https://openweathermap.org/api)

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/Shalvigour/Weather-app.git
cd Weather-app
```

**2. Add your API key**

Open `script.js` and replace the placeholder with your API key:
```javascript
const API_KEY = "YOUR_API_KEY_HERE";
```

**3. Run the app**

Simply open `index.html` in your browser — no server or build step needed:
```bash
# Option 1 — Direct open
open index.html

# Option 2 — VS Code Live Server (recommended)
# Right-click index.html → Open with Live Server
```

---

## 🔐 Security Note

> ⚠️ **Never commit your real API key to GitHub.**
>
> The OpenWeatherMap API key should be kept private. For local development, replace the key in `script.js` directly. For deployment, use environment variables or a backend proxy to keep the key hidden.

To prevent accidental commits, store the key in a separate config file and gitignore it:
```
config.js
.env
```

---

## 🎯 Key Concepts Demonstrated

- Async/Await with `fetch()` for REST API calls
- Browser Geolocation API for live location detection
- Dynamic DOM manipulation based on API response
- Error handling for invalid city names and denied location access

---

## 👩‍💻 Author

**Shalvi Gour** — [GitHub](https://github.com/Shalvigour)
