# Weather Dashboard

A React weather dashboard that lets you search any city and view current conditions plus a 5-day forecast.

## Project structure

```
weather-dashboard/
├── public/              # Static assets
├── src/
│   ├── components/      # UI components (SearchBar, WeatherCard, Forecast)
│   ├── hooks/           # Custom React hooks (useWeather)
│   ├── services/        # API calls (OpenWeatherMap)
│   ├── types/           # TypeScript interfaces
│   ├── App.tsx          # Root layout
│   ├── main.tsx         # Entry point
│   └── index.css        # Global styles
├── .env.example         # API key template
├── index.html
├── package.json
└── vite.config.ts
```

## Prerequisites

- [Node.js](https://nodejs.org/) 18 or later

## Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Copy the environment file and add your API key:

   ```bash
   cp .env.example .env
   ```

   Get a free key at [OpenWeatherMap](https://openweathermap.org/api).

3. Start the dev server:

   ```bash
   npm run dev
   ```

4. Open the URL shown in the terminal (usually `http://localhost:5173`).

## Scripts

| Command         | Description              |
| --------------- | ------------------------ |
| `npm run dev`   | Start development server |
| `npm run build` | Production build         |
| `npm run preview` | Preview production build |
