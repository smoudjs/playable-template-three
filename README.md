# Playable Template with Three.js

A starter template for creating playable ads using Three.js with TypeScript support. This template combines:

- [Three.js](https://threejs.org/) - 3D graphics library for creating immersive WebGL experiences
- [@smoud/playable-sdk](https://github.com/smoudjs/playable-sdk#readme) - SDK for creating playable ads with standardized events and methods
- [@smoud/playable-scripts](https://github.com/smoudjs/playable-scripts#readme) - Build and development tools optimized for playable ads

## Demo

Try out this template:
- [View on CodePen](https://codepen.io/peter-hutsul/pen/VYwygKp)

## Features

- Three.js integration for high-performance 3D graphics
- TypeScript support for better development experience
- Hot module replacement during development
- Game structure with Three.js and SDK integration
- Event handling (resize, pause, resume, volume, etc.)
- Installation button implementation
- Interaction tracking
- Responsive 3D scene scaling
- GLTF model loading and animation
- Proper lighting setup
- Smooth animation loop management

## Getting Started

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development server:
   ```bash
   npm run dev
   ```
4. Build for production:
   ```bash
   npm run build
   ```

## Project Structure

- `src/index.ts` - Main entry point with SDK, Three.js and Game initialization
- `src/Game.ts` - Game logic and Three.js scene setup
- `src/index.css` - Styles for your playable
- `src/index.html` - HTML template
- `assets/` - Directory for your game assets (3D models, textures, etc.)

## Looking for More?

Check out other available templates for different frameworks and use cases:

- [playable-template-base](https://github.com/smoudjs/playable-template-base) - Template base version
- [playable-template-base-js](https://github.com/smoudjs/playable-template-base-js) - Template base version (JavaScript)
- [playable-template-phaser](https://github.com/smoudjs/playable-template-phaser) - Template with Phaser
- [playable-template-pixi](https://github.com/smoudjs/playable-template-pixi) - Template with PixiJS
- [playable-template-pixi-spine](https://github.com/smoudjs/playable-template-pixi-spine) - Template with PixiJS and Spine
