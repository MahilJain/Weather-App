# Weather App

A modern, responsive weather application built with vanilla JavaScript that provides real-time weather information for any location worldwide.

## Features

- 🌤️ Current weather conditions display
- 📍 Location-based weather detection
- 🔍 Search weather by city name
- 📱 Responsive design for all devices
- 🌡️ Temperature in Celsius
- 💨 Wind speed and 💧 Humidity 

## Demo

[https://mahiljain.github.io/Weather-App/]

## Screenshots

![Weather App Screenshot](![Screenshot 2025-05-30 132808](https://github.com/user-attachments/assets/940f5441-55f6-4c6d-ac17-d73981912031)
)
*Main weather display*

*City search functionality*

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
```

2. Open `index.html` in your browser or serve with a local server:
```bash
# Using Live Server (VS Code extension)
# Right-click index.html → "Open with Live Server"
```

## API Setup

This app uses the OpenWeatherMap API. To run the application:

1. Sign up for a free API key at [OpenWeatherMap](https://openweathermap.org/api)
2. Create a `config.js` file in the root directory:
```javascript
const API_KEY = 'a978b67eab76abe3dc6922545d1ea467';
const API_URL = 'https://api.openweathermap.org/data/2.5';
```

## Usage

1. **Default Location**: The app will request your location on first load
2. **Search**: Use the search bar to find weather for any city
3. **Refresh**: Click the refresh button to update current conditions


## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and responsive design
- **JavaScript (ES6+)** - Application logic
- **OpenWeatherMap API** - Weather data
- **Fetch API** - HTTP requests

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Features in Detail

### Current Weather
- Real-time temperature, humidity, and pressure
- Weather condition with descriptive icons
- Wind speed 
- Visibility information

### Location Services
- Manual city search

### Responsive Design
- Mobile-first approach
- Touch-friendly interface
- Optimized for tablets and desktops
- Progressive Web App ready

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Development

### Running Locally
```bash
# Install dependencies (if using build tools)
npm install

# Start development server
npm start

# Build for production
npm run build
```

### Code Style
- Use ES6+ features
- Follow camelCase naming convention
- Add comments for complex functions
- Maintain consistent indentation (2 spaces)

## API Rate Limits

- Free tier: 1,000 calls/day
- Consider implementing caching for production use
- Rate limiting handled gracefully with user feedback

## Troubleshooting

### Common Issues

**API Key Errors**
- Ensure your API key is valid and active
- Check that `config.js` is properly configured
- Verify API key permissions

**Location Not Found**
- Check internet connection
- Ensure location services are enabled
- Try searching with country code (e.g., "London, UK")

**Slow Loading**
- Check network connection
- API might be temporarily unavailable
- Clear browser cache

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Icons from [Weather Icons](https://erikflowers.github.io/weather-icons/)
- Inspiration from various weather apps and UI designs

## Contact

Mahil  - (mailto: mahiljee001@gmail.com)

---

⭐ Star this repo if you found it helpful!
