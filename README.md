# OpenWeatherMap API in Swagger docs

This project converts key OpenWeatherMap endpoints into a well structured, human-readable OpenAPI format using Swagger.

**Note:** You must sign up for an API key at [OpenWeatherMap](https://openweathermap.org/city/2643743)
---
## What's inside

Endpoints, such as Weather [current-weather.yaml], Forecast [forecast.yam], and Geocoding (Direct/Reverse) [geocoding.yaml] endpoints are documented using Swagger.OpenAPI 3.0 specification

---
## Platforms used
- [Swagger Editor](https://editor.swagger.io)
- YAML syntax with OpenAPI 3.0
- Tested using OpenWeatherMap's public API

---
## How it works
1. Open Swagger Editor(https://editor.swagger.io)
2. Place the  content off yaml from OpenWeatherMap (`/Weather`, `/Forecast`, `/Geocoding`)
3. Add the actual OpenWeatherMap API key in the appid **query**, and the city name in the **q** query
4. Send the request and observe the responses such as `200 OK` and `401 Unauthorized`

---
## Sample
- City: `q=trichy`
- API key: `appid=Your-API-key`
- Latitude: `lat=0.7905`
- Longitude: `lon=78.7047`

---
## Writer
Written and documented by Prasanna.

