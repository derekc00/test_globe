# Globe.gl Simple Example

A simple interactive 3D globe visualization using [globe.gl](https://github.com/vasturiano/globe.gl).

## Features

- Interactive 3D globe with Earth night texture
- Random colored points scattered across the globe
- Animated arcs connecting random locations
- Auto-rotation
- Mouse controls (drag to rotate, scroll to zoom)

## Getting Started

### Option 1: Using npm (recommended for development)

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the local server:
   ```bash
   npm start
   ```

3. Open your browser and navigate to `http://localhost:8080`

### Option 2: Direct browser opening

Simply open `index.html` in a modern web browser. Note that some browsers may block external resources when opening local files directly, so using a local server is recommended.

## Controls

- **Drag**: Rotate the globe
- **Scroll**: Zoom in/out
- **Right-click + Drag**: Pan the view

## Customization

You can customize the globe by modifying the `index.html` file:

- Change the globe texture by modifying the `globeImageUrl()`
- Add more points or arcs by adjusting the data arrays
- Modify colors, sizes, and animation speeds
- Change the initial camera position with `pointOfView()`

## Resources

- [Globe.gl Documentation](https://github.com/vasturiano/globe.gl)
- [Three.js Documentation](https://threejs.org/docs/)
