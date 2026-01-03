# Solar System Explorer Starter

This repository contains a minimal Three.js Solar System Explorer scaffold. It sets up a Three.js scene with orbit controls, a sun, and a couple of planets that orbit the sun.

## Features

- Basic scene setup with camera, renderer, and lighting
- OrbitControls for interactive exploration
- Simple sun and two orbiting planets (Earth and Mars) with basic orbital motion

## Getting Started

### Prerequisites

You need a local web server to serve the `index.html` file. You can use [http-server](https://www.npmjs.com/package/http-server) or any static server of your choice.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/scalinity/solar-system-explorer-starter.git
cd solar-system-explorer-starter
```

2. Install `http-server` globally if you don't have it:

```bash
npm install -g http-server
```

### Running the app

Start the local server in the project directory:

```bash
http-server .
```

Then open your browser to the address shown (typically http://localhost:8080) and you should see the solar system visualization.

Alternatively, you can open `index.html` directly, but some browsers restrict module imports for local files.

## Customization

The `index.html` file includes comments to help you extend the scene with additional planets, textures, or more complex orbital mechanics.

## License

This project is provided as-is for educational purposes.
