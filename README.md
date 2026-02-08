# toda - Universe Explorer (WebAssembly)

An astronomical visualization application running in your browser.

## Live Demo

Visit: https://jsuk.github.io/toda-wasm/

## Features

- **Real-time Sky Visualization**: View the sky from any location on Earth
- **Moon Phase Display**: Accurate moon phase based on your current date/time and location
- **Multiple View Modes**:
  - Universe Explorer: Navigate through space
  - Planet Surface: View the sky from Earth's surface
  - Moon Observer: Detailed moon phase observation

## Controls

| Key | Action |
|-----|--------|
| WASD / Arrow Keys | Move camera |
| Mouse | Look around |
| Q / E | Roll |
| +/- | Zoom |
| M / Tab | Toggle view mode |
| G | Toggle grid |
| S | Toggle stars |
| T | Toggle time flow |
| F | Toggle FPS display |
| H | Toggle HUD |

## Browser Features

- Uses your browser's **geolocation** to show the sky from your location
- Uses your browser's **system clock** for accurate current sky position
- Supports **fullscreen** mode

## Requirements

- Modern web browser with WebGL support
- JavaScript enabled

## Building from Source

This is the pre-built WebAssembly version. For the full source code and build instructions, see the main repository.

## Credits

Based on Mitaka by Tsunehiko Kato and the 4D2U Project.
Built with SDL3, OpenGL, and Emscripten.

## License

See the main repository for license information.
