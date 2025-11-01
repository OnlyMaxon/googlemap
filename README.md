# Google Map - 2D World Map with Countries

A fully functional 2D map application displaying country boundaries with zoom capabilities.

## Features

- ✅ **2D Map View**: Clean roadmap view (not satellite or 3D)
- ✅ **Zoom Functionality**: Fully working zoom with mouse wheel and +/- buttons
- ✅ **Country Focus**: Displays country boundaries and labels prominently
- ✅ **Interactive**: Click anywhere on the map to interact
- ✅ **Responsive**: Works on different screen sizes

## Setup Instructions

### Option 1: Using with Google Maps API Key (Recommended)

1. Get a Google Maps API key from [Google Cloud Console](https://console.cloud.google.com/)
2. Enable the "Maps JavaScript API" for your project
3. Open `index.html` and replace `YOUR_API_KEY` with your actual API key:
   ```html
   src="https://maps.googleapis.com/maps/api/js?key=YOUR_ACTUAL_API_KEY&callback=initMap"
   ```
4. Open `index.html` in a web browser

### Option 2: Quick Test (Limited functionality)

For testing purposes without an API key, you can use a development/testing key, but features will be limited.

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
├── index.html          # Google Maps API version (requires API key)
├── map-simple.html     # Standalone version (works without API key)
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

- Google Maps JavaScript API
- HTML5
- CSS3
- Vanilla JavaScript

## License

MIT License