# GeoWeather

A responsive weather dashboard built with React, Vite, TypeScript, and Leaflet. It combines live weather data with an interactive map so users can explore current conditions, hourly and daily forecasts, and air quality metrics for different cities and custom map-selected locations.

Live Demo: [GeoWeather Demo](https://geoweather.netlify.app/)


## Features

- Interactive map with clickable location selection
- City-based weather lookup with preloaded locations
- Current weather panel with condition details
- Hourly and 3-day forecast cards
- Air quality and pollution insights
- Dark themed, responsive dashboard UI
- Real-time data integration through WeatherAPI and MapTiler

## Tech Stack

- React 19
- Vite
- TypeScript
- Tailwind CSS
- Leaflet + React Leaflet
- TanStack Query
- WeatherAPI
- MapTiler

## Project Showcase

### Desktop View

![GeoWeather Desktop Dashboard](docs/screenshots//Screenshot%20From%202026-11-14%2018-37-04.png)

### Mobile View

![GeoWeather Mobile Dashboard](docs/screenshots/Screenshot%20From%202026-11-14%2018-57-10.png)

## Screenshots

![GeoWeather Screenshots](docs/screenshots/Screenshot%20From%202026-11-14%2018-37-38.png)

## How It Works

1. Pick a city from the location selector or click anywhere on the map.
2. The app fetches weather data for the selected coordinates or city.
3. The dashboard updates with current conditions, forecast cards, and pollution data.
4. Map overlays can be toggled to visualize weather layers over the map.

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Installation

```bash
npm install
```

### Environment Variables

Create a `.env.local` file in the root of the project and add the following keys:

```bash
VITE_API_KEY=your_weatherapi_key
VITE_MAPTILER_KEY=your_maptiler_key
```

You can obtain:

- a WeatherAPI key from [WeatherAPI](https://www.weatherapi.com/)
- a MapTiler key from [MapTiler](https://www.maptiler.com/)

### Run the App

```bash
npm run dev
```

Open the local URL displayed in the terminal (usually `http://localhost:5173`).

### Production Build

```bash
npm run build
```

## Project Structure

```bash
src/
  api.ts
  App.tsx
  types.ts
  components/
    cards/
    dropdowns/
    skeletons/
    ui/
    Map.tsx
    MapLegend.tsx
    SidePanel.tsx
    WeatherIcon.tsx
  schemas/
    weatherSchemas.ts
public/
  favicon.svg
  icons.svg
```


