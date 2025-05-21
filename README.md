# OpenWeatherMap API in Swagger docs

This project converts key OpenWeatherMap endpoints into a well-structured, human-readable OpenAPI format using Swagger.

**Note:** You must sign up for an API key at [OpenWeatherMap](https://openweathermap.org/city/2643743)
---
## What's inside

The following YAML files contain OpenWeatherMap endpoint specifications written in Swagger/OpenAPI 3.0:
- `current-weather.yaml`: Current weather data
- `forecast.yaml`: 5-day/3-hour weather forecast
- `geocoding.yaml`: Direct and Reverse Geocoding

---
## Platforms used
- [Swagger Editor](https://editor.swagger.io)
- YAML syntax with OpenAPI 3.0
- Tested using OpenWeatherMap's public API

---
## How it works
1. Open [Swagger Editor](https://editor.swagger.io)
2. Copy and paste the content of yaml from OpenWeatherMap (`/Weather`, `/Forecast`, `/Geocoding`)
3. Add the actual OpenWeatherMap API key in the appid **query**, and the city name in the **q** query
4. Send the request and observe the responses such as `200 OK` and `401 Unauthorized`

---
## Sample
- City: `q=trichy`
- API key: `appid=Your-API-key`
- Latitude: `lat=10.7905`
- Longitude: `lon=78.7047`

---
## Writer
Written and documented by Prasanna.

