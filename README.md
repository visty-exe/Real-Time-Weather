# 🌦️ Real-Time Weather App

A modern, responsive weather application built with **React, Vite, Tailwind CSS, and the OpenWeatherMap API**. Search for a city and instantly explore its current weather conditions through a clean, glassmorphism-inspired interface.

<p align="center">
  <a href="https://github.com/visty-exe/Real-Time-Weather">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository" />
  </a>
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 19" />
  <img src="https://img.shields.io/badge/Vite-Frontend-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

---

## ✨ Features

- **Live Weather Data** — Fetch current weather conditions for searched cities.
- **City Search** — Enter a location to retrieve its weather information.
- **Debounced Search** — Reduce unnecessary API requests while typing.
- **Temperature Display** — View the current temperature in Celsius.
- **Feels-Like Temperature** — Understand how the weather feels outside.
- **Humidity Information** — Check the current relative humidity.
- **Wind Speed** — View reported wind speed.
- **Weather Conditions** — See the current weather description.
- **Modern UI** — Glassmorphism-inspired cards, a scenic background, and clean typography.
- **Responsive Layout** — A flexible interface built with Tailwind CSS utilities.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | Component-based user interface |
| Vite | Development server and production build |
| Tailwind CSS 4 | Styling and layout |
| Axios | HTTP requests to the weather API |
| JavaScript (ES Modules) | Application logic |
| OpenWeatherMap API | Current weather data |
| ESLint | Code quality and linting |

## 📸 Application Preview

<!-- Add a screenshot of your application here -->
<!-- Save your screenshot as screenshots/weather-app.png -->

<!--
<p align="center">
  <img src="screenshots/weather-app.png" alt="Real-Time Weather App preview" width="800" />
</p>
-->

*Tip: Add a screenshot of the application here to showcase the interface directly on your GitHub repository.*

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- npm
- An [OpenWeatherMap API key](https://openweathermap.org/api)

### 1. Clone the repository

```bash
git clone https://github.com/visty-exe/Real-Time-Weather.git
cd Real-Time-Weather
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure the API key

Create a `.env` file in the root directory:

```env
VITE_API=your_openweathermap_api_key
```

The application reads this environment variable to make requests to the OpenWeatherMap Current Weather API.

**Important:** Never commit your `.env` file or expose API credentials in public repositories. Variables prefixed with `VITE_` are bundled into client-side code, so this setup is suitable for a public demo key but does not keep the key secret. Use a backend proxy if you need to protect the credential.

### 4. Start the development server

```bash
npm run dev
```

Open the local URL printed in your terminal, usually `http://localhost:5173`.

## 📦 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the Vite development server |
| `npm run build` | Builds the application for production |
| `npm run preview` | Previews the production build locally |
| `npm run lint` | Runs ESLint checks |

## 🌐 Weather API

This application uses the [OpenWeatherMap Current Weather Data API](https://openweathermap.org/current).

The application requests weather information using the city name and metric units.

Example request format:

```text
https://api.openweathermap.org/data/2.5/weather?q=London&units=metric&APPID=YOUR_API_KEY
```

The response provides weather information such as:

- City name
- Current temperature
- Feels-like temperature
- Weather conditions
- Relative humidity
- Wind speed

An active internet connection and a valid API key are required to retrieve live data.

## 🧠 What I Learned

This project helped me practice:

- Building reusable React-based interfaces.
- Managing input and application state with React Hooks.
- Integrating third-party REST APIs using Axios.
- Implementing debounced user input.
- Working with environment variables in Vite.
- Styling interfaces using Tailwind CSS.
- Displaying API-driven data dynamically.
- Using ESLint and Vite development tools.

## 🔮 Future Improvements

- [ ] Automatic weather detection using browser geolocation.
- [ ] Hourly and multi-day forecasts.
- [ ] Weather icons and condition-based backgrounds.
- [ ] Celsius/Fahrenheit unit switching.
- [ ] Search suggestions and recent locations.
- [ ] Loading indicators and clearer API error messages.
- [ ] Responsive refinements for smaller screens.
- [ ] Sunrise, sunset, and additional weather metrics.

## 👨‍💻 Author

**Vishal Tyagi**

Full Stack Developer | MERN Stack & Java

- GitHub: [@visty-exe](https://github.com/visty-exe)
- Project: [Real-Time-Weather](https://github.com/visty-exe/Real-Time-Weather)

---

If you found this project useful, consider giving the repository a ⭐.

