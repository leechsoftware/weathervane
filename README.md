<p align="center">
  <img src="docs/images/icon.png" width="180" height="180" alt="The Weathervane app icon">
</p>

<h1 align="center">Weathervane</h1>

<p align="center">
  <a href="https://apps.apple.com/app/id6812456607"><img alt="Download Weathervane on the App Store" src="https://img.shields.io/badge/Download-on%20the%20App%20Store-0A84FF?style=for-the-badge&logo=apple&logoColor=white" height="42"></a><br>
  <sub>Listed on the App Store as <strong>Dashboard for ECOWITT Weather</strong></sub>
</p>

<p align="center">
  <strong>Everything your Ecowitt weather station measures, on one clear screen.</strong><br>
  For iPhone, iPad, Mac and Apple Watch. Free, with no ads, no account and no tracking.
</p>

<p align="center">
  <img alt="iPhone and iPad: iOS 17 or later" src="https://img.shields.io/badge/iPhone%20%2B%20iPad-iOS%2017%20or%20later-2b2b33?style=for-the-badge&logo=apple&logoColor=white">
  <img alt="Mac: macOS 14 or later" src="https://img.shields.io/badge/Mac-macOS%2014%20or%20later-2b2b33?style=for-the-badge&logo=apple&logoColor=white">
  <img alt="Apple Watch: watchOS 10 or later" src="https://img.shields.io/badge/Apple%20Watch-watchOS%2010%20or%20later-2b2b33?style=for-the-badge">
  <img alt="Free" src="https://img.shields.io/badge/Price-Free-2b2b33?style=for-the-badge">
</p>

> [!IMPORTANT]
> **This repository is not a download.** It holds Weathervane's documentation and its issue
> tracker. There is no source code and no app file here: the app is closed source and is
> only available from the App Store.
>
> **Get the app: [apps.apple.com/app/id6812456607](https://apps.apple.com/app/id6812456607)**

<p align="center">
  <a href="https://leechsoftware.github.io/weathervane/media/weathervane-demo.mp4"><img src="docs/images/weathervane-demo.gif" width="300" alt="Weathervane's dashboard scrolling from the outdoor temperature through the forecast, radar, charts and sensor cards"></a><br>
  <sub><a href="https://leechsoftware.github.io/weathervane/media/weathervane-demo.mp4">Watch the full demo video</a> · recorded in the app's own demo mode, with sample data</sub>
</p>

## What it is

Weathervane is a dashboard for Ecowitt weather stations. It connects to your gateway or
console over your own Wi-Fi, or to Ecowitt Cloud from anywhere, and shows live conditions at
the top, a tile for every reading, then charts, records, forecast and radar. It keeps your
history, tracks your records, and alerts you when something matters.

You can try all of it without a station: choose **Just show me a sample dashboard** on the
first screen.

## Screenshots

These are the screenshots from the App Store listing.

### iPhone

<p align="center">
  <img src="docs/images/iphone-01.jpg" width="230" alt="The dashboard: outdoor temperature on a thermometer, with indoor, wind, rain and pressure tiles">
  <img src="docs/images/iphone-02.jpg" width="230" alt="The dashboard in dark mode">
  <img src="docs/images/iphone-03.jpg" width="230" alt="The wind compass with a day of wind history, the Rainfall card and the Garden card">
</p>
<p align="center">
  <img src="docs/images/iphone-04.jpg" width="230" alt="The 5-day forecast and weather radar">
  <img src="docs/images/iphone-05.jpg" width="230" alt="The Garden and Comfort cards above the history charts">
  <img src="docs/images/iphone-06.jpg" width="230" alt="History charts for humidity, wind and rainfall">
</p>
<p align="center">
  <img src="docs/images/iphone-07.jpg" width="230" alt="History charts for pressure, solar radiation and soil moisture">
  <img src="docs/images/iphone-08.jpg" width="230" alt="Sensor cards: lightning, air quality, and temperature and humidity sensors">
  <img src="docs/images/iphone-09.jpg" width="230" alt="Alert settings for rain, wind and pressure">
</p>
<p align="center">
  <img src="docs/images/iphone-10.jpg" width="230" alt="A full-screen chart of a soil moisture sensor over seven days">
</p>

### Mac

<p align="center">
  <a href="https://github.com/leechsoftware/weathervane-mac"><img src="docs/images/mac-01.jpg" width="820" alt="Weathervane in the Mac menu bar with its panel open, and cards on the desktop"></a><br>
  <sub>The Mac version has its own page: <a href="https://github.com/leechsoftware/weathervane-mac">leechsoftware/weathervane-mac</a></sub>
</p>

### iPad

<p align="center">
  <img src="docs/images/ipad-01.jpg" width="270" alt="The two-column iPad dashboard">
  <img src="docs/images/ipad-02.jpg" width="270" alt="The iPad dashboard in dark mode">
  <img src="docs/images/ipad-03.jpg" width="270" alt="History charts and sensor cards on an iPad">
</p>

### Apple Watch

<p align="center">
  <img src="docs/images/watch-01.png" width="200" alt="The Apple Watch app showing temperature, humidity, indoor temperature, rain, wind and UV">
</p>

## What it shows

- Outdoor temperature with today's high and low, feels like, humidity and dew point
- Indoor temperature and humidity
- Pressure with its 3-hour trend and a barometer outlook
- Wind speed, gusts and direction on a compass that also shows where the last day's wind came from
- Rain rate and totals for the hour, day, event, week, month and year
- Solar radiation and UV index
- Sunrise, sunset, daylight, moon phase, moonrise and moonset
- Lightning count and distance
- Air quality: PM2.5, PM10, CO2 and AQI
- Soil moisture and temperature, leaf wetness, water level, water leaks
- Battery and signal for every sensor
- Daily, monthly and all-time records
- A 5-day forecast adjusted to your own station, radar and weather warnings

## Documentation

| Page | What it covers |
|---|---|
| [Getting started](docs/getting-started.md) | Installing the app, the first screen, and demo mode |
| [Connecting your station](docs/connecting.md) | Ecowitt Cloud or your own Wi-Fi, and which to choose |
| [Supported hardware](docs/supported-hardware.md) | Gateways, consoles and sensors |
| [Features](docs/features.md) | The dashboard, history, records, forecast and radar |
| [Alerts](docs/alerts.md) | What can alert you, and when alerts are checked |
| [Mac version](https://github.com/leechsoftware/weathervane-mac) | The Mac app has its own documentation |
| [Apple Watch, widgets and Siri](docs/watch-widgets-siri.md) | Your station away from the app |
| [Coverage by region](docs/regions.md) | What works in the US, Europe and elsewhere, and languages |
| [Privacy and data sources](docs/privacy.md) | Where your readings go, and who supplies the forecast and radar |
| [Questions and answers](docs/faq.md) | Common questions and fixes |
| [What's new](docs/whats-new.md) | Recent versions |

## Support

- **A bug or a feature request:** [open an issue](https://github.com/leechsoftware/weathervane/issues/new/choose) here, or use **Contact us** in the app's About screen, which attaches a short report about your devices.
- **Support pages:** [iPhone, iPad and Apple Watch](https://leechsoftware.com/dashboard-for-ecowitt/) · [Mac](https://leechsoftware.com/dashboard-for-ecowitt-mac/)
- **Privacy policy:** [leechsoftware.com/weathervane-for-ecowitt/privacy.html](https://leechsoftware.com/weathervane-for-ecowitt/privacy.html)

Please do not post your Ecowitt application key, API key or account password in an issue.

## About this repository

Weathervane is made by [Leech Software, Inc.](https://leechsoftware.com) The app is closed
source. The text and images in this repository are © Leech Software, Inc. and are here to
document the app; they are not released under an open licence.

Weathervane is independently developed and is not affiliated with or endorsed by Ecowitt.
Ecowitt and its product names are trademarks of their owners.
