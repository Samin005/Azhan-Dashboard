# Azhan Dashboard

A comprehensive yet simple Islamic prayer times dashboard built with vanilla HTML, CSS, and JavaScript. Designed for Muslims to track daily prayer times, view inspirational Islamic content, and stay connected with their faith through automated Adhan calls and rotating Quranic verses, Hadiths, Duas, and spiritual reminders.

## Features

- **Real-Time Clock & Date**: Displays current time, Gregorian date, and optional Hijri (Islamic) date
- **Prayer Times**: Accurate prayer times for Fajr, Dhuhr, Asr, Maghrib, and Isha based on your location
- **Next Prayer Countdown**: Live countdown to the next prayer with visual highlighting and flashing alerts
- **Weather Integration**: Current temperature display using Open-Meteo API
- **Sunrise/Sunset Times**: Displays daily sunrise and sunset times
- **Rotating Backgrounds**: Beautiful Islamic-themed background images that rotate every 10 seconds
- **Inspirational Content Rotation**: Automatically cycles through Hadiths, Quranic verses, Duas (supplications), and spiritual reminders
- **Announcement Ticker**: Scrolling announcement bar with customizable messages
- **Audio Features**:
  - Automated Adhan (call to prayer) playback at prayer times
  - Optional Dua (supplication) after Adhan
  - Volume control and voice selection (currently supports Mecca voice)
  - Test and stop audio controls
- **Customizable Settings**:
  - Location-based prayer times (set city and country)
  - Toggle display options (Hijri date, weather, ticker, 12-hour time format)
  - Audio settings (enable/disable Adhan and Dua)
  - Content rotation speed adjustment
- **Responsive Design**: Works on desktop and mobile devices
- **Offline-Capable**: Core functionality works without internet (except for API-dependent features like weather and Hijri dates)

## How to Use

### Local Viewing

1. Clone or download this repository.
2. Open `Azhan.html` in your web browser.
3. (Optional) For full functionality, run a local server where you have cloned:

   ```bash
   python -m http.server 8000
   ```

   Then open `http://localhost:8000/Azhan.html` in your browser.
4. Configure your location in the settings panel (gear icon) for accurate prayer times.

### Online Viewing

- View live on GitHub Pages: [https://samin005.github.io/Azhan-Dashboard/Azhan.html](https://samin005.github.io/Azhan-Dashboard/Azhan.html)

## APIs Used

- **Aladhan API**: For prayer times and Hijri date calculations
- **Open-Meteo API**: For weather data
- **Geocoding API**: For converting city/country to coordinates

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you'd like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Screenshot

![screenshot](./resources/Screenshot%202026-04-07%20215633.png)