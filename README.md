# Solar System Explorer

An interactive 3D visualization of our solar system built with Three.js. Features realistic planet orbits, stunning visual effects, and smooth controls for exploring the cosmos.

## Features

- **All 8 Planets** - Mercury through Neptune with accurate relative sizes, colors, and axial tilts
- **Glowing Sun** - Multi-layered sun with corona effect and animated solar flares
- **Saturn's Rings** - Beautiful ring system with Cassini Division gap
- **Uranus Rings** - Subtle cyan-tinted rings on Uranus
- **Earth's Moon** - Orbiting moon around Earth
- **15,000 Star Background** - Immersive starfield with color variations (white, blue, yellow tints)
- **Bloom Post-Processing** - Beautiful glow effects using UnrealBloomPass
- **Orbit Paths** - Subtle orbital path visualization (toggleable)
- **Planet Labels** - Floating labels above each planet (toggleable)
- **Interactive Controls**:
  - Drag to rotate view
  - Scroll to zoom
  - Click any planet to smoothly focus camera on it
- **UI Controls**:
  - Toggle orbit lines
  - Toggle planet labels
  - Pause/Play animation
  - Reset view button
  - Speed control slider (0x - 3x)

## Getting Started

### Quick Start (Recommended)

Simply open `index.html` directly in a modern browser. The app uses ES modules via import maps, which most browsers support natively.

### Using a Local Server

For the best experience, serve the file with a local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Controls

| Action          | Control                   |
| --------------- | ------------------------- |
| Rotate view     | Click and drag            |
| Zoom            | Scroll wheel              |
| Pan             | Right-click drag          |
| Focus on planet | Click on planet           |
| Toggle orbits   | Click "Orbits" button     |
| Toggle labels   | Click "Labels" button     |
| Pause/Resume    | Click "Pause" button      |
| Reset camera    | Click "Reset View" button |
| Adjust speed    | Use speed slider          |

## Technical Details

- Built with Three.js r160
- Uses EffectComposer for post-processing
- UnrealBloomPass for glow effects
- OrbitControls for camera interaction
- Procedurally generated planet textures
- Responsive design with window resize handling

## Planet Data

Each planet is configured with:

- Accurate relative size
- Realistic orbital distance (scaled for visibility)
- Axial tilt matching real values
- Orbital speed based on actual ratios
- Unique color and emissive properties

## Browser Support

Works best in modern browsers with ES module support:

- Chrome 89+
- Firefox 89+
- Safari 15+
- Edge 89+

## License

This project is provided as-is for educational purposes.
