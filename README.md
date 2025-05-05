# Weather Application

A simple and elegant weather application that provides real-time weather information for any city worldwide.

## Features

- Real-time weather data for any city
- Temperature display in Celsius
- Humidity percentage
- Wind speed in km/h
- Weather condition icons
- Error handling for invalid city names

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- OpenWeatherMap API

## Setup Instructions

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Create a configuration file:
   - Create a new file named `config.js` in the root directory
   - Add your OpenWeatherMap API key:
```javascript
const config = {
    apiKey: "your-api-key-here"
};
```

3. Get an API key:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/api)
   - Get your free API key
   - Replace "your-api-key-here" in config.js with your actual API key

## Usage

1. Open `index.html` in your web browser
2. Enter a city name in the search box
3. Click the search button or press Enter
4. View the current weather information for the specified city

## Project Structure

```
project/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # Main JavaScript file
├── config.js           # Configuration file (not tracked by git)
└── images/             # Weather icons
```

## Security Note

- The `config.js` file containing the API key is not tracked by git
- Never commit your API key to version control
- Keep your API key secure and don't share it publicly

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Weather icons from [OpenWeatherMap](https://openweathermap.org/weather-conditions)
