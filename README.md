# ☀️ Daily Weather

> A beautiful and intuitive weather web application for real-time weather updates

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

## 📋 Overview

Daily Weather is a sleek, user-friendly weather application that provides real-time weather information for any location worldwide. Get instant access to current conditions, forecasts, and detailed weather data with a beautiful, responsive interface.

## ✨ Features

- 🌍 **Location Search**: Find weather for any city worldwide
- 🌡️ **Real-Time Data**: Get current temperature, humidity, wind speed, and more
- 📅 **Weather Forecast**: View multi-day weather predictions
- 🎨 **Beautiful UI**: Clean, modern design with weather-based themes
- 📱 **Fully Responsive**: Perfect experience on desktop, tablet, and mobile
- ⚡ **Fast & Lightweight**: Optimized for quick loading and smooth performance
- 🌓 **Dynamic Backgrounds**: Weather conditions reflected in the UI
- 📍 **Geolocation Support**: Auto-detect your current location

## 🛠️ Tech Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with animations and transitions
- **JavaScript**: Dynamic functionality and API integration
- **Weather API**: Real-time weather data integration

## 📁 Project Structure

```
DAILY-WEATHER/
├── .vscode/                # VSCode configuration
├── .env.Example            # Environment variables template
├── .gitignore              # Git ignore rules
├── config.js               # Configuration settings
├── desktop.ini             # Windows desktop settings
├── index.html              # Main HTML file
└── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have:
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A weather API key (e.g., from OpenWeatherMap, WeatherAPI, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/daily-weather.git
   cd daily-weather
   ```

2. **Set up API credentials**
   
   Copy the `.env.Example` file and create your own `.env` file:
   ```bash
   cp .env.Example .env
   ```

3. **Configure your API key**
   
   Open `config.js` or `.env` and add your weather API key:
   ```javascript
   const API_KEY = 'your_api_key_here';
   const API_URL = 'https://api.weatherapi.com/v1';
   ```

4. **Open in browser**
   
   Simply open `index.html` in your web browser:
   ```bash
   # For a simple local server (optional)
   python -m http.server 8000
   # or
   npx serve
   ```
   
   Then navigate to `http://localhost:8000`

## 🔧 Configuration

### Getting a Weather API Key

1. **OpenWeatherMap** (Recommended)
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate your API key
   - Free tier includes 1,000 calls/day

2. **WeatherAPI.com** (Alternative)
   - Visit [WeatherAPI.com](https://www.weatherapi.com/)
   - Create a free account
   - Get your API key
   - Free tier includes 1 million calls/month

### Customization

Edit `config.js` to customize:
```javascript
const config = {
  apiKey: 'YOUR_API_KEY',
  units: 'metric', // 'metric' or 'imperial'
  language: 'en',
  defaultCity: 'London'
};
```

## 🎯 Features in Detail

### Current Weather
- Temperature (Celsius/Fahrenheit)
- Weather condition description
- "Feels like" temperature
- Humidity percentage
- Wind speed and direction
- Visibility
- UV index
- Sunrise and sunset times

### Search Functionality
- City name search
- Autocomplete suggestions
- Recent searches history
- Geolocation detection

### Weather Forecast
- 5-day forecast
- Hourly predictions
- Temperature trends
- Precipitation probability

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📱 Responsive Design

Daily Weather is fully responsive and works seamlessly on:
- 🖥️ Desktop (1920px and above)
- 💻 Laptop (1024px - 1919px)
- 📱 Tablet (768px - 1023px)
- 📱 Mobile (320px - 767px)

## 🚀 Deployment

### Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings
3. Navigate to Pages section
4. Select branch and folder
5. Click Save

### Deploy to Netlify

1. Sign up at [Netlify](https://netlify.com)
2. Connect your GitHub repository
3. Configure build settings (if needed)
4. Deploy!

### Deploy to Vercel

1. Sign up at [Vercel](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Ideas
- 🎨 Add new themes or color schemes
- 🌍 Add more language support
- 📊 Add weather charts and graphs
- 🔔 Add weather alerts and notifications
- ⭐ Add favorite locations feature

## 📝 To-Do List

- [ ] Add dark mode toggle
- [ ] Implement weather alerts
- [ ] Add weather radar map
- [ ] Create mobile app version
- [ ] Add voice search
- [ ] Implement PWA features
- [ ] Add weather widgets

## 🐛 Known Issues

- None at the moment! 🎉

If you find any bugs, please [open an issue](https://github.com/yourusername/daily-weather/issues).

## 👨‍💻 Author

Kavindu Rathnayaka
