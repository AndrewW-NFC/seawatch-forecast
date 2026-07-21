# Seawatch Forecast

Seawatch Forecast is a small static web app for interpreting local seawatching conditions at Shadmoor State Park and Montauk Point.

It uses live weather and marine forecast data to give a plain-language read on:

- whether seabirds may be pushed closer to shore
- whether viewing conditions are likely to be clean or difficult
- whether glare, shimmer, wind, waves, or visibility may affect the watch
- what gear is likely to be useful

The app is designed for GitHub Pages and currently runs as a single `index.html` file.

## Data

Weather and marine forecast data come from [Open-Meteo](https://open-meteo.com/).

This app is a birding interpretation of forecast model data. It is not a safety forecast, navigation tool, or replacement for official marine weather guidance.

## Development

Open `index.html` in a browser, or serve the folder locally with any simple static file server.

For example:

```sh
python3 -m http.server 4173
```

Then visit:

```text
http://localhost:4173
```

## License

MIT
