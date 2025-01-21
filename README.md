# Weather_App
An app which helps you to check the weather of a city. 
you can check it out here : https://remarkable-cendol-df62af.netlify.app/



# Weather App

A modern, responsive weather application built with React, TypeScript, and Tailwind CSS that provides real-time weather information and air quality data for any location worldwide.

![Weather App Screenshot](https://images.unsplash.com/photo-1504608524841-42fe6f032b4b?auto=format&fit=crop&q=80&w=1200)

## Features

- **Real-Time Weather Data**: Get current weather conditions for any location
- **Air Quality Information**: Detailed air quality metrics including CO, NO2, O3, and PM2.5 levels
- **Responsive Design**: Beautiful, mobile-first interface that works on all devices
- **Dynamic Weather Icons**: Visual representation of current weather conditions
- **Detailed Metrics**: 
  - Temperature in Celsius
  - Wind Speed
  - Humidity Levels
  - UV Index
  - Precipitation

## Technology Stack

- **Frontend Framework**: React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **API**: WeatherAPI.com

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

1. Enter a location in the search bar (city name, postal code, or coordinates)
2. Press Enter or click the search icon
3. View detailed weather information and air quality data for the specified location

## API Integration

The app uses the WeatherAPI.com service to fetch weather data. The API provides:
- Current weather conditions
- Location information
- Air quality data
- Weather condition icons

## Project Structure

```
src/
├── App.tsx        # Main application component
├── main.tsx       # Application entry point
├── index.css      # Global styles
└── vite-env.d.ts  # TypeScript declarations
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Weather data provided by [WeatherAPI.com](https://www.weatherapi.com/)
- Icons by [Lucide](https://lucide.dev/)
