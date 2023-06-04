# Weather Forecasting Web Application

This is a command-line tool that accepts a city's name and returns the current weather forecast. It leverages the OpenWeatherMap API to fetch weather data and parse it using Python.

## Features

- Fetches current weather forecast for a specific city using the OpenWeatherMap API.
- Displays the weather information including temperature, humidity, wind speed, and description.
- Handles errors gracefully and provides helpful error messages.
- Command-line interface for easy usage.

## Getting Started

These instructions will help you set up and run the weather forecasting tool on your local machine.

### Prerequisites

- Python 3.x
- OpenWeatherMap API key
- Flask

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/2202-Aryan/weather_forcasting/
   
 ## Usage
Set your OpenWeatherMap API key:

1. Replace <YOUR_API_KEY> in config.py with your actual OpenWeatherMap API key. 
  If you don't have one, you can sign up and obtain a free API key from OpenWeatherMap.
2. Run the application:
   python weather_forecast.py --city <city_name>
## Error Handling
- If the city name is not provided or invalid, an error message will be displayed.
- If there is an issue connecting to the OpenWeatherMap API or retrieving weather data, an error message will be displayed.

   
