# World Map with Countries (Leaflet, no Google)

A fully functional 2D map application displaying country boundaries with zoom capabilities. No Google services are used. Both pages use Leaflet + OpenStreetMap.

## Features

- ✅ **2D Map View**: Clean roadmap view (not satellite or 3D)
- ✅ **Zoom Functionality**: Fully working zoom with mouse wheel and +/- buttons
- ✅ **Country Focus**: Displays country boundaries and labels prominently
- ✅ **Interactive**: Click anywhere on the map to interact
- ✅ **Responsive**: Works on different screen sizes

## Setup Instructions

### How to run (no API keys needed)

1. Open `index.html` or `map-simple.html` directly in your browser, or use VS Code Live Server.
2. You’ll see a world map with all countries outlined. Hover to highlight, click a country to zoom.

Notes:
- Uses OpenStreetMap tiles and Leaflet.
- Country boundaries are loaded from a public GeoJSON dataset at runtime.

### Notes

- Uses OpenStreetMap tiles and Leaflet from public CDNs.
- Country boundaries are loaded from a public GeoJSON dataset at runtime.

## Usage

1. **Zoom In/Out**: 
   - Use mouse wheel to scroll
   - Click the +/- buttons on the right side
   - Use pinch gesture on touch devices

2. **Pan**: 
   - Click and drag to move around the map

3. **View Countries**: 
   - Country borders are highlighted in blue
   - Zoom in to see more details
   - Country labels appear at appropriate zoom levels

## File Structure

```
.
├── index.html          # Leaflet + OSM (полная версия, без Google)
├── map-simple.html     # Leaflet + OSM (упрощённая версия, без Google)
├── TESTING.md          # Testing documentation and verification results
└── README.md           # This file
```

## Map Configuration

The map is configured with the following settings:

- **Initial Position**: Centered at latitude 20°, longitude 0° (world view)
- **Initial Zoom Level**: 3 (showing most of the world)
- **Map Type**: Roadmap (2D) only
- **Controls**: Zoom, Map Type, and Fullscreen controls enabled
- **Styling**: Custom styles to emphasize country boundaries

## Browser Compatibility

- Chrome/Edge: ✅ Fully supported
- Firefox: ✅ Fully supported
- Safari: ✅ Fully supported
- Mobile browsers: ✅ Fully supported

## Technologies Used

- Leaflet
- OpenStreetMap tiles
- Public GeoJSON dataset for country boundaries
- HTML5, CSS3, Vanilla JavaScript

## License

MIT License