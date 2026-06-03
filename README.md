# 🌤️ SkyCast — Modern Weather Dashboard

[![React](https://img.shields.io/badge/React-19.0-61DAFB?style=flat-square&logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-4.5-646CFF?style=flat-square&logo=vite)](https://vitejs.dev/)
[![Material UI](https://img.shields.io/badge/Material--UI-6.0-007FFF?style=flat-square&logo=mui)](https://mui.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

SkyCast is an elegant, responsive, and feature-rich weather dashboard built with **React**, **Vite**, and **Material UI**. It connects to the **OpenWeatherMap API** to fetch real-time weather information and presents it in a premium glassmorphic UI. 

### 🔗 **[Live Demo on Vercel](https://weather-app-two-psi-80.vercel.app/)**

---

## ✨ Features

* **🎨 Theme Mode Toggle**: Instantly switch between custom-designed **Light** and **Dark** themes.
* **🌡️ Dynamic Weather Backgrounds**: The background gradient changes dynamically depending on the active weather condition and temperature (Warm gold for hot climates, frosty ice-blue for cold, and slate-grey for rain!).
* **📊 Comprehensive Weather Stats Grid**: View real-time temperature, min/max values, "feels like" temperature, atmospheric pressure, wind speed, and humidity in a clean responsive grid.
* **🔍 Integrated Search Bar**: A smooth, inline search input adorned with search icons. It formats input strings into proper city names (e.g., searching `"london"` correctly renders as `"London, GB"`).
* **⚠️ Error & Fallback Control**: Displays graceful, slide-down banners if the API key is unconfigured or a city is not found.

---

## 🛠️ Tech Stack

* **Frontend**: React 19, Vite, Javascript (ES6+)
* **Styling & UI**: Material UI (MUI v6), `@mui/icons-material` for crisp modern vectors
* **API**: [OpenWeatherMap API v2.5](https://openweathermap.org/api)
* **Hosting**: Vercel

---

## ⚙️ Local Setup and Installation

### 1. Clone the repository
```bash
git clone https://github.com/Bhupendra-Kumar-1/weather-app.git
cd weather-app
```

### 2. Install dependencies
```bash
npm install
```

### 3. Setup Environment Variables
Create a file named `.env` in the root directory of your project and insert your OpenWeatherMap API Key:
```env
VITE_WEATHER_API_KEY=your_openweathermap_api_key_here
```
> *Note: You can get your free API key by signing up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).*

### 4. Run the Development Server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.

### 5. Build for Production
```bash
npm run build
```

---

## 🚀 Deploying to Vercel

Since you are deployed on Vercel, make sure you configure your environment variables in the Vercel Dashboard:

1. Navigate to your project on **Vercel** ➡️ **Settings** ➡️ **Environment Variables**.
2. Add a new variable:
   * **Key**: `VITE_WEATHER_API_KEY`
   * **Value**: *Your OpenWeatherMap API key*
3. Click **Save** and trigger a **Redeploy** on your latest deployment.

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
