# 🗺️ Venue Map Explorer

Interactive map app built with **React**, **Leaflet** and **React Router**.

- 📍 Jump to your current location (browser geolocation) and drop a pin there
- 🖱️ Click anywhere on the map to add markers
- 📌 10 curated London venues (galleries, markets, parks) with a description for each pin
- 🌍 Load a remote set of venues (Berlin) from a JSON API
- 🗺️ OpenStreetMap tiles, no API key required

**Stack:** React 18 · react-leaflet · Leaflet · React Router · Bootstrap

## Run locally

```bash
npm install
npm start        # http://localhost:3000
```

## Deploy

Static site, deploys as-is on **Vercel** (framework preset: *Create React App*).
`vercel.json` rewrites every path to `index.html` so client-side routes such as `/map` work on refresh.

## Notes

The venues fetched from the "Berlin" option come from a public mock server
(`my-json-server.typicode.com/franciscoghp/db-places`), backed by the [`db-places`](https://github.com/franciscoghp/db-places) repository.
