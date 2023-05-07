# SkySight: Weather Dashboard

SkySight is a simple and intuitive weather dashboard that provides users with up-to-date weather information for any location. With SkySight, you can quickly access current weather conditions, short-term forecasts, and long-term forecasts in a user-friendly interface.

## Skysight is a work in progress

## Features

- Search for a location or use your current location (using the Geolocation API)
- Display current weather conditions, including temperature, humidity, wind speed, and an icon representing the weather (e.g., sunny, cloudy, rainy)
- Show a short-term forecast for the next few hours and a longer-term forecast for the next several days
- Allow users to switch between Celsius and Fahrenheit temperature units

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Node.js (LTS version recommended, visit https://nodejs.org/ to download and install)
- npm (Node.js package manager, it comes with Node.js)
- Git (Visit https://git-scm.com/ to download and install)
- API key for the weather data provider (e.g., OpenWeatherMap or WeatherAPI)

### Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/skysight.git
```

2. Change to the project directory:

```
cd skysight
```

3. Install dependencies:

```
npm install
```

4. Create a `.env` file in the project root directory and add your weather API key:

```
WEATHER_API_KEY=your_api_key_here
```

5. Run the development server:

```
ember serve
```

Open your web browser and navigate to `http://localhost:4200/` to view the application.

## Deployment

To build the application for production, run:

```
ember build --environment=production
```

The compiled assets will be available in the `dist/` folder. Deploy the contents of this folder to your preferred hosting provider.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/api) or [WeatherAPI](https://www.weatherapi.com/)
- Built with [Ember.js](https://emberjs.com/)

---

**Note**: Be sure to replace placeholders (e.g., `yourusername`, `your_api_key_here`) with your actual information. Customize the README to match your project's details and requirements.
