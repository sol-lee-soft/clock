# Desk Clock/Weather Station

[!\[Launch Terminal](https://img.shields.io/badge/LAUNCH-TERMINAL-00ff66?style=for-the-badge\&logo=opsgenie\&logoColor=black\&labelColor=111318)](https://sol-lee-softe.github.io/clock/index.html)

A minimalist, high-contrast standalone web terminal designed to function as a low-glare desk clock/weather station. Optimized specifically for mobile screen boundaries and responsive touch-control layouts.

## Key Features

* **Ambient Chrono Core:** A large, high-contrast digital time readout displaying hours, minutes, and seconds.
* **Dual-Station Telemetry Matrix:**

  * **\[ HOME ] Mode:** Locks onto a fixed, user-defined home base ZIP code to monitor headquarters weather from anywhere in the world.
  * **\[ LOCAL ] Mode:** Pings the device's native HTML5 Geolocation GPS array to pull real-time weather conditions on the move.
* **Atmospheric Data Pipeline:** Automatically converts live radar payloads from the Open-Meteo API into Fahrenheit, humidity percentages, and barometric inches of mercury (`IN`).
* **Zero-Baggage Architecture:** Built entirely inside a single standalone HTML file using local browser caching (`localStorage`) instead of a heavy backend database server.

## Installation \& Mobile Shortcut Deployment

1. Rename your weather station code file to `index.html` and commit it to the root of your `clock` repository.
2. Ensure GitHub Pages is turned on for the main branch of that repository.
3. Open the direct live URL in your mobile browser: `https://sol-lee-soft.github.io/clock/index.html`
4. Open your browser's settings menu and tap **"Add to Home Screen"**.
5. Launch the application from your phone's desktop to run it as a full-screen, zero-touch standalone ambient utility terminal.

