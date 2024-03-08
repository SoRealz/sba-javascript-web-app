# sba-javascript-web-app
# Weather Application

This simple weather application allows users to check the current weather conditions for a specific city. It utilizes the OpenWeatherMap API to retrieve weather data and displays key information such as temperature, humidity, and wind speed. The application also provides visual representation of the weather condition with corresponding icons.

## Getting Started

To use this weather application, you need to obtain an API key from OpenWeatherMap. Follow these steps:

1. Visit [OpenWeatherMap](https://openweathermap.org/) and sign up for a free account.
2. Once logged in, navigate to the API keys section to generate a new API key.
3. Copy the generated API key.

## Installation

1. Clone or download the repository to your local machine.

```bash
git clone https://github.com/your-username/weather-application.git
```

2. Open the project in your preferred code editor.

3. Replace the placeholder API key with the one you obtained from OpenWeatherMap.

```javascript
const apiKEY = "YOUR_OPENWEATHERMAP_API_KEY";
```

## Usage

1. Open the `index.html` file in a web browser.

2. Enter the name of the city in the search input box.

3. Click the search button to retrieve and display the current weather information.

## Features

- Displays temperature in Celsius.
- Visual representation of weather conditions with corresponding icons.
- Handles errors gracefully, displaying an error message when the city is not found.

## Customization

You can customize the visual representation of weather conditions by replacing the image URLs in the code. Images are currently loaded based on the main weather condition (Clouds, Clear, Rain, Drizzle, Mist).

```javascript
// Example for Clouds
weatherIcon.src = "images/clouds.png";
```

Feel free to replace the images in the `images` folder with your own icons.

## Credits

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/).

*Made with Love<3 by Jacob Sorrell*