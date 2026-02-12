# Route Distance Calculator

A lightweight web app for measuring running and cycling route distances on interactive maps.

## Features

- 🗺️ Interactive map with your current location
- 📏 Draw routes and see real-time distance measurements
- ↶ Undo last route if you make a mistake
- 🎨 Multiple color-coded routes in one session
- 📱 Works on desktop and mobile
- 🆓 Completely free - no API keys or sign-up required

## How to Use

1. Open the app (it will request your location)
2. Click the **ruler icon** (⚑) in the top-left to start drawing
3. Click on the map to trace your running or cycling route
4. See distance measurements appear at each point
5. **Double-click** or press **ESC** to finish the route
6. Click **Undo** to remove the last route
7. Use the **unit toggle** to switch between km and miles

## Live Demo

Visit: https://[your-username].github.io/ki-map-measure/

## Technology

Built with:
- [Leaflet](https://leafletjs.com/) - Open-source mapping library
- [OpenStreetMap](https://www.openstreetmap.org/) - Free map tiles
- [Leaflet.PolylineMeasure](https://github.com/ppete2/Leaflet.PolylineMeasure) - Distance measurement plugin

Distance calculations use the Haversine formula for accurate great-circle distances on Earth's surface.

## Local Development

Simply open `index.html` in a web browser. No build process or server required.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers with geolocation support

## License

MIT License - Free to use and modify

## Credits

Created with [Claude Code](https://claude.com/claude-code)
