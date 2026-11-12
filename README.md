# 🌤️ SkyCast — Modern Weather Dashboard

> **Note on Engineering Background:** This project represents frontend engineering practice utilizing **React 19**, **Vite**, and **Material UI**. My current primary career focus is **Java Full Stack Development (Java, Spring Boot, React, MySQL)**.

[![React](https://img.shields.io/badge/React-19.2-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-4.5-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Material UI](https://img.shields.io/badge/Material--UI-v6-007FFF?style=flat-square&logo=mui&logoColor=white)](https://mui.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

**SkyCast** is an elegant, responsive weather dashboard built with **React**, **Vite**, and **Material UI**. It connects to the **OpenWeatherMap API** to fetch real-time weather metrics and presents them in a modern glassmorphic interface.

🔗 **Live Deployment:** [https://weather-app-two-psi-80.vercel.app/](https://weather-app-two-psi-80.vercel.app/)

---

## ✨ Features

* **Theme Mode Toggle:** Switch seamlessly between light and dark visual themes.
* **Dynamic Weather Backgrounds:** Visual gradient adapts based on weather conditions and ambient temperature.
* **Comprehensive Metrics Grid:** Real-time temperature, min/max values, feels-like indicator, atmospheric pressure, wind speed, and humidity.
* **Integrated Search:** Inline search input formatted to handle geographic city names.
* **Graceful Error Handling:** Fallback banners for network latency, missing API keys, or invalid location searches.

---

## 🛠️ Technology Stack

- **Framework:** React 19 (`react`, `react-dom`)
- **UI Components:** Material-UI (`@mui/material`, `@mui/icons-material`, `@emotion/react`, `@emotion/styled`)
- **Build Tool:** Vite 4.5
- **API:** OpenWeatherMap Current Weather Data REST API
- **Deployment:** Vercel

---

## 📂 Project Structure

```text
weather-app/
├── public/              # Static assets and icons
├── src/
│   ├── assets/          # Weather condition icons
│   ├── components/      # UI widgets (SearchBar, InfoBox, WeatherApp)
│   ├── App.jsx          # Root component
│   ├── index.css        # Global CSS resets
│   └── main.jsx         # App mounting point
├── index.html           # HTML template
├── package.json         # Dependencies
└── vite.config.js       # Vite configuration
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bhupendra-Kumar-1/weather-app.git
   cd weather-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory:
   ```env
   VITE_WEATHER_API_KEY=your_openweathermap_api_key
   ```

4. **Run the local development server:**
   ```bash
   npm run dev
   ```

---

## 👨‍💻 Author
**Bhupendra Kumar**  
- GitHub: [@Bhupendra-Kumar-1](https://github.com/Bhupendra-Kumar-1)  
- LinkedIn: [linkedin.com/in/bhupendra-kumar-dev](https://www.linkedin.com/in/bhupendra-kumar-dev/)
