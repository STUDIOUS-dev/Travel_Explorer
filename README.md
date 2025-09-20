# Travel Explorer

Travel Explorer is a simple and beautiful web app that lets you discover any city or place in the world. Enter a destination to instantly see a photo gallery and the latest weather forecast for that location.

## Features
- Search for any city or place
- View a curated photo gallery powered by Unsplash
- Get real-time weather information from OpenWeatherMap
- Clean, responsive, and modern UI

## Live Demo
The website is live at: [https://travel-explorer-sigma.vercel.app/](https://travel-explorer-sigma.vercel.app/)

## How It Works
- Enter a destination in the search bar
- The app fetches photos from Unsplash and weather data from OpenWeatherMap
- Results are displayed instantly with a smooth user experience

## Tech Stack
- HTML, CSS (Tailwind), JavaScript
- Unsplash API
- OpenWeatherMap API

## Getting Started
1. Clone this repository:
   ```sh
   git clone https://github.com/studious-dev/Travel_Explorer.git
   ```
2. Open the `Frontend/P2/index.html` file in your browser.
3. (Optional) Replace the API keys in the script section with your own for higher rate limits.

## Customization
- You can change the default city loaded on page open by editing the `fetchDestinationData('Jaipur')` line in the JavaScript.
- To use your own API keys, sign up at [Unsplash Developers](https://unsplash.com/developers) and [OpenWeatherMap](https://openweathermap.org/api), then update the constants in the script.

## Credits
- Photos: [Unsplash](https://unsplash.com)
- Weather: [OpenWeatherMap](https://openweathermap.org)

## License
This project is open source and available under the [MIT License](LICENSE).
