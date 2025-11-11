# RetroArch Emscripten

Pre-built RetroArch WebAssembly cores for browser-based retro gaming emulation.

## Installation

```bash
npm install @rebitplay/retroarch-emscripten
```

## Usage

This package contains pre-built RetroArch cores compiled to WebAssembly/Emscripten. You can use these cores to run retro games in the browser.

### Available Cores

The package includes cores for various gaming systems including:
- Nintendo (NES, SNES, Game Boy, Game Boy Color, Game Boy Advance)
- Sega (Genesis, Master System, Game Gear)
- Sony PlayStation
- Arcade systems (MAME, FinalBurn Alpha)
- And many more...

### Example

```javascript
// Import or reference the cores from the 1.21.0 directory
import libretro from '@rebitplay/retroarch-emscripten/1.21.0/libretro.js';
```

## Version

This package contains RetroArch build version 1.21.0.

## License

MIT
