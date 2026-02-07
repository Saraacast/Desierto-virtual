# Desierto Virtual 🏜️

An interactive 3D virtual reality desert scene built with A-Frame and WebGL.

## Features

- **Interactive Desert Environment**
  - Yellow sand terrain
  - Sand dunes with realistic colors
  - Rocky landscape elements
  - Decorative stones

- **Flora**
  - 4 dark green cacti with pink flowers
  - Scattered across the desert

- **Landmarks**
  - Main orange pyramid in the center
  - Interactive brown sphere

- **Lighting System**
  - Realistic moon lighting
  - Ambient light for desert atmosphere
  - Directional light rays
  - Point light for sand highlights

- **Interactivity**
  - Click the brown sphere to change the sky color to light blue (2-second effect)
  - Free camera controls with mouse

## How to Use

1. **Open in Browser**: Simply open `desierto.html` in any modern web browser
2. **Using a Local Server**: 
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000/desierto.html`

3. **Interact with the Scene**:
   - Click on the brown sphere to see the sky change
   - Use mouse to navigate around the desert

## Technologies

- **A-Frame** - WebGL/WebXR framework for easy 3D web development
- **HTML5** - Structure
- **JavaScript** - Interactivity and event handling

## Project Structure

```
.
├── desierto.html      # Main virtual reality scene
├── README.md          # This file
└── .github/
    └── copilot-instructions.md
```

## Browser Compatibility

Works on any modern browser that supports WebGL:
- Chrome/Chromium
- Firefox
- Safari
- Edge

Enjoy exploring the virtual desert! 🌟
