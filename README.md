# BettAir

BettAir is a web application that helps users make more informed travel decisions by displaying real-time air quality data.

The app uses live environmental data APIs to show current AQI (Air Quality Index) and help users identify cleaner areas in Philadelphia.

## Features

- Uses browser geolocation to detect user location

- Fetches real-time AQI data from AirNow

- Geocodes locations using Geocodio

- Displays AQI with color-coded health categories

- Simple, fast Flask backend

## Tech Stack

- Python (Flask)

- JavaScript

- Leaflet.js (map rendering)

- AirNow API

- Geocodio API

## Environment Variables

This project requires a .env file with the following API keys:

```bash
AIRNOW_API_KEY=your_airnow_api_key_here
GEOCODIO_API_KEY=your_geocodio_api_key_here
```
Create a .env file in the root directory of the project and add the keys above.

Do NOT commit your .env file to GitHub.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/sriramJ24/CleanRoute.git
cd CleanRoute
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Add your .env file with the required API keys.
```bash
AIRNOW_API_KEY=your_airnow_api_key_here
GEOCODIO_API_KEY=your_geocodio_api_key_here
```
4. Run the app:
```bash
python run.py
```
5. Open in browser:
```bash
http://127.0.0.1:5000
```
## Future Improvements

- Route comparison based on AQI

- Historical air quality trends

- Expanded geographic coverage

- Mobile optimization

Built for hackathon/demo purposes.